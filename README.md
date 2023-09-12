# diverse scattered borkedness

Tracking bugs, caveats, reminders and ramblings in and of my public clones/forks.


## Examples / tests

- local repo issue reference, flavour A:  #1
- local repo issue reference, flavour B:  GH-1
- local repo issue reference, flavour C:  *URK*
- other repo's issue ref, flavour A:  diverse_scattered_borkedness#1
- other repo's issue ref, flavour B:  GerHobbelt/diverse_scattered_borkedness#1
- other *forked* repo's issue ref, flavour B':  MrBonkers/W#1
- other *forked* repo's issue ref, case-insensitive=_mistake?_, flavour B":  mrbonkers/W#1
- other *forked* repo's issue ref, flavour B3: using old name of original repo, before we forked:  MrBonkers/diverse_scattered_borkedness#1
- other repo's issue ref, flavour C:  W#1
- other repo's issue ref, flavour D:  GerHobbelt/W#1
- other repo's issue ref, flavour E (copy&pasted *OLD* full `https://` link):  https://github.com/GerHobbelt/diverse_scattered_borkedness/issues/1
- other repo's issue ref, flavour E (copy&pasted *NEW* full `https://` link):  https://github.com/GerHobbelt/W/issues/1
- other repo's issue ref, flavour E' (copy&pasted *OLD* *forked* full `https://` link):  https://github.com/MrBonkers/diverse_scattered_borkedness/issues/1
- other repo's issue ref, flavour F' (copy&pasted *NEW* *forked* full `https://` link):  https://github.com/MrBonkers/W/issues/1

Conclusion: [GitHub docs: Issues and pull requests](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/autolinked-references-and-urls#issues-and-pull-requests) may *say* `#1` and `GH-1` SHOULD work, but they DON'T in the `README.md` file. ... 🤔 Sure enough, those work in any *commit*, though? ... 🥳 [*yup*!](https://github.com/MrBonkers/W/commit/13117d92be205426482d0e2bf7db135cfbc7fc82)
