# Lab Report 4

## Basic set up
1. open up vis Studio code
2. click on the terminal button on top left corner of screen
3. click on new terminal button from the drop down options
Here is an example:
![Set up](https://github.com/angelocake/cse15l-LabReport4/assets/130005453/7b73323b-3b38-49b2-879c-aa63c1ed723f)

## Steps 4-9

### Step 4 (log into ieng)
1. click on the terminal you just opened
2. type in `ssh` followed by your `ieng6 email` (eample `ssh cs15lsp12ab@ieng6.ucsd.edu` . note: don't type this email)
Note: This ssh command is used to start the process of signing into an ieng6 account.
3. press the `<enter>` button

![ssh](https://github.com/angelocake/cse15l-LabReport4/assets/130005453/2689364c-c8e5-4b07-8d11-1e059ef9b0f9)

4. Type in your password for the `ieng6` email
5. press the `<enter>`
Note: Password will give no indication of what you typed so be careful. Also, if correct password it will look similar to the image below.
![correct password](https://github.com/angelocake/cse15l-LabReport4/assets/130005453/2d250752-54e7-46f7-b4e3-7140c4684631)

### Step 5 (Clone your fork of the repository from your Github account)
1. Click this link to get code [github repository](https://github.com/ucsd-cse15l-s23/lab7)
2. Click the fork button on top right of screen to get you code onto your github account
3. Click on the green create fork button atr bottom of page
Page looks like below and this is where you make your own fork
![github fork](https://github.com/angelocake/cse15l-LabReport4/assets/130005453/b85c2891-539c-4568-94dc-38ebb50d376a)
4. Click on the drop down for the green Code button
5. Get a copy of the https for this github (will be used in following steps)
![copy hhtps](https://github.com/angelocake/cse15l-LabReport4/assets/130005453/739d9a1c-18fc-42e0-9746-c4e2a9427b42)

6. Go to click on your terminal in vis code
7. Type `git clone ` and paste your address you copied earlier
Note: this `git clone` command is used to clone a repository into your current working directory.
8. Press `<enter>`
Note: typing the command `ls` then `<enter>` will show the forked repository file in your current directory 
9. type `cd Lab7` and press `<enter>` to move into the Lab7 directory where the following steps will take place

Below is an example terminal making it's way to the Lab7 repository (red numbers are the corrisponding steps)
![copy repository](https://github.com/angelocake/cse15l-LabReport4/assets/130005453/044bb8ec-35ef-49dc-ac17-26bb3ed003d7)


### Step 6 (Testing and showing failure)
1. Make sure that you are in the Lab7 directory (can be done in a simple `ls` command then `<enter>` to make sure you are in the right directory. Alternatively the `pwd` can also be used)
2. In the terminal type `sh ./tests.sh` (This command is used to run a tester on the current directory)
3. Press `<enter>`
4. Look at bottom left where it shows results and note that it says that the program ran 2 tests but one of them happened to fail

![Test1](https://github.com/angelocake/cse15l-LabReport4/assets/130005453/c2ab67af-87c0-4452-95f5-b4e68a54ed8a)


### Step 7 (Editting ListExamples.java)
1. Type `vim ListExample.java` into the terminal (the `vim` command is used to take over the terminal to allow for someone to make edits to the java file.)
2. Press `<enter>`
3. Type `?ind` and then press `<enter>` (the `?ind` is basically a search in the current file for the last instance of the characters ind in that order.)
Note: The image below is the result of doing the vim command(step 1) and sets up step 3 
**![vim-step1thru3](https://github.com/angelocake/cse15l-LabReport4/assets/130005453/0adfbb39-fd8f-4e1d-810c-f3ad74fa4c36)
4. Press the `e` button (goes to the end of the current word)
5. Press `r` (gets ready to replace the current character)
6. Press `2` (will replace the number 1 with the number 2)
![changing 1to2](https://github.com/angelocake/cse15l-LabReport4/assets/130005453/ff296f70-9fd5-43f7-b2dc-ac007831e1d6)
7. Type `:wq` (command to save and exit the current vim file)
8. Press `<enter>` (if done correctly, should exit you out of the ListExample.java file)
![save and exit](https://github.com/angelocake/cse15l-LabReport4/assets/130005453/8db3f9c0-52cd-4385-90bb-82a6fd472c64)


### Step 8 (Retesting and showing success)
1. In the terminal type `sh ./tests.sh` (This command is used to run a tester on the current directory)
2. Press `<enter>`
Note: this should compile and rerun the tests with the update we made in mind.
3. Look at bottom left where it shows results and note that it says that the program ran 2 tests and that both turned out ok/passed.

The image below shows how your terminal should look if the tests pass
![New test](https://github.com/angelocake/cse15l-LabReport4/assets/130005453/1ff67146-6ffc-40fe-ba27-9908c7c906e3)


### Step 9 (Commit and push changes to Github)
1. Type `git add ListExamples.java` and press `<enter>`   (Should prepare to push your edit to github)
2. Type `git commit -m "fixed ListExamples.java"` and press `<enter>` (Will push your edit to github)
3. To ensure that you updated github type `git status` and press `<enter>` because it will show the files that are not updated on github (`git status` shows the files that are ready to be pushed to update github and files that are different than that of github.)
(basically just read the highlighted red files to ensure that ListExamples.java is not there. Note: if you see ListExamples.class in red it is perfectly fine.)
![Push github](https://github.com/angelocake/cse15l-LabReport4/assets/130005453/4c42cb75-8f79-487b-867d-1c7442ed42c6)
    
