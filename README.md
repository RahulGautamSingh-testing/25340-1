# 25340-1

Test Details:

1. Create a repo with one package and one 2 labels in renoavte config
2. Renovate the repo ... now repo has one update PR which has 2 labels
3. Remove the labels in renovate config
4. Renovate the repo ... now update PR has no labels
5. Re-add 2 labels to the renovate config
6. Renovate the repo ... now update PR has 2 labels

INFO: Goal is to confirm that the new logic handles deletion of all labels and re-addition of labels to such a repo
