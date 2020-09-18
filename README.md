# How to run cppcheck ?

Create a file named 'cppcheck.yml' under .github/workflows with the contents of the file I have in my repository with the same name. If your Makefile is inside some folder in the repo, provide it's path after a space in the last line of the code of this yml file. 
Example:
run: cppcheck MiniProject_C/3_Implementation

P.S: The .github/workflows folder shoud automatically have created if you have already run Build.

After creating the file, go to Actions tab in your repo and go to cppcheck-action where you can check the status of your cppcheck.
Create a status badge and copy status badge markdown and paste it in your readme.md file. Then your badge will be created.
