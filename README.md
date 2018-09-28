# merge-conflict-practice
At least two key things could have been done to avoid all of this:
1. When working in a shared repository, always work in a non-master branch, and
1. Whenever possible, avoid working in the same file as someone else

The fresh pull from master makes sense. It put all four characters at the same starting point, so any differences in their initial code would be papered over. However, it would've been better to parallelize the project by seeing if there were any other features not in FUBAR.md that could be done while one group was working in FUBAR. After the merge, all members should have pulled from the master branch in order to make sure they were working from the same point, even if they weren't working in FUBAR; otherwise the missing code will be noted as a change that might get added with an accidental git add -A. Finally, they should have been working in different branches after the first merge conflict had been resolved and everyone had pulled in the merged changes from that resolved master branch.
