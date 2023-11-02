# How use cd
1) Move in folder in terminal ```cd NameOfFolder```
2) Move back in folder ```cd ../```
3) Dont forget save the progress CTRL+S
# How to make pull request:
1) Create a new branch ```git checkout -b new-test-branch```
2) Select the files you want to send ```git add ```
3) Add a commit ```git commit -m "test commit"```
4) Take a push commit ```git push origin new-test-branch```
5) Open a project on GitHub ```https://github.com/MrColteR/TelegramBot```
6) Create a pull request on your branch
7) Link your branch to your issue using ```#number_of_your_issue```
# How to get pull request:
Pull request ```git pull```
# How to make rebase:
1) Checkout to your branch ```checkout test-branch```
2) Do rebase ```git rebase master```
3) If you haven't conflicts. You are good.
4) If you have conflicts  
   4.1 Fix conflicts in file (name of file will be in console)  
   4.2 Enter the command ```git rebase --continue```  
   4.3 If you have more conflicts, repeat 4.1 and 4.2  
   4.4.1 Would you can't resolve the conflict, you may skip conflict ```git rebase --skip```  
   4.4.2 Would you want cancel rebase ```git rebase --abort```  
# How to delete a branch locally on your computer:
1) remove branch ```git branch -D nameOfBranch```
# How to delete a branch on github:
1) Go to the branch that need to be deleted on Github ```git checkout nameOfBranch```
2) Push with parameter ```git push --delete nameOfBranch```