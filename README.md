# CMSC320 Homework Assignment 1

This is the first homework assignment for CMSC320, Spring 2024 with Dr. Alam, on Git, Pandas, and SQL.

This is just basic practice using git.

**If you do not have a GitHub Account yet, please make one (It will help you in the future).**

# Git Assignment

1. Create a **.txt** file on your computer in an empty directory answering the question **"Why are you interested in taking CMSC320?"**

2. Then, in the same empty directory, create an empty file called **data.DAT** (It is *crucial* the file is called only **data.DAT**)

3. Then, fork this directory by clicking fork in github. In **your** forked copy of the repository, go to 'Code', and copy the https clone key. 

4. Open a command prompt on your computer, and go to some empty directory. Then, type 'git clone *key*' into the command line (where *key* is whatever https link github gave you). 
   - To **commit/push/pull** from the command line you must first **set it up** by inserting your credentials (*username* & *email*). Read the following documentation: <a href="https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git" target="_blank">Git Username Link</a> & <a href="https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address" target="_blank">Git Email Link</a>
   - If you have **two-factor authentication on** for your GitHub Account, then you need to use a ***personal access token** as your password instead since they removed authentication through the password: <a href="https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens" target="_blank">Personal Access Token Info Link</a>
   - If you have **VSCode**, you can also integrate your GitHub Account via the VSCode UI: <a href="https://code.visualstudio.com/docs/sourcecontrol/github" target="_blank">Working with GitHub in VS Code</a>
```
git config user.name your_username
git config user.email your_email
```
5. Move the **two** files you created into the cloned directory (**your downloaded fork**). 

6. Now you need to find a way using a standard git reference to **upload your answers in the text file to your fork on github on the main branch, which should be public**. However, using a .gitignore, your **data.DAT** file should **not** be on the main branch of your repository. You **need to use a .gitignore for this task to receive full credit**.

The documentation on git is available here: <a href="https://git-scm.com/docs" target="_blank">Git Documentation Link</a>

Please note you should be mostly interested in the **add** command, and instructions for making a .gitignore here: <a href="https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files" target="_blank">gitignore Link</a>

When you are ready to submit, **turn in the link to your git project with your assignment**. Please do so by **submitting a PDF with the github link**! This *must* work for credit! 

# Additional Git Details
*For macOS Users: Don't worry about the extra .DS_Store file*

There are plenty other details about git we will not discuss in this tutorial. This is simply a primer on the basic functionality of the tool. Primarily, merge conflicts and branch management can be severe problems with git repositories. 

In general, repositories are collections of code and files, stored on a **local** device (your machine) and **remote** device (github servers, say). Each of these repositories can have multiple **branches**, or versions of the code. Sometimes, when **merging** versions of the code from the local branch to the remote branch, or between branches, there may be a conflict that git does not know how to resolve (conflicting versions of a file). These are 'merge conflicts', and can be read more about here: <a href="https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line" target="_blank">Merge Conflict Link</a>

General structure of git can be read more about here: <a href="https://www.oreilly.com/library/view/version-control-with/9781449345037/ch04.html#:~:text=Git%20places%20only%20four%20types,Git's%20higher%20level%20data%20structures.&text=Each%20version%20of%20a%20file%20is%20represented%20as%20a%20blob" target="_blank">Git Structure Link</a>
