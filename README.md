# Git_Workshop
This repository helps you to practice Git hands-on :+1:  



<a name="Headings"></a>
Git supports the following heading formats:

```
# A first-level heading
## A second-level heading
### A third-level heading
```

<a name="Git Commands"></a>
Helpers on basic command line interfaces used in Github. The usage of CLI is to have a log of operations and configurations. They are redundant if Git Desktop App is installed and used to perform operations.

Some basic Git commands executed using the Git CLI:

```
git help <command>
git <command> --help
git config --list
git status
git clone <repository_url>
git add <filename.extension>
git commit
git push
git remote -v

```

git config --list           - Displays the set of current git configuration in your local PC  

git status                  - Lists all new or modified files that are not committed  

git clone                   - Clones the repository provided its url from the   

git add                     - Adds a new file to teh existing repository in the specified file structure  

git commit                  - Commits the new/modified file enry to a new repository or to the existing repository file organization  

git push                    - Push the changes to the remote GitHub repository  
    
git remote -v               - Shows the set of fetch and pull operations carried out in the repository  





**Task for the Teams:**


![Task](https://github.com/GitWorkshopWWCDSPracticeAccount/Git_Workshop/assets/128200371/6f2c39be-7430-4f1f-b047-23ba30227a8f)




**Tast 1**

Create a Review Issue with your Squad name and perform the operations mentioned in the snapshot actions. 

Example: "Review Code changes by Squad 1 - Bingo"
Assignee: Assign to a team member of your Squad
Link to project
Link to Development branch 'Test_Branch_for_Squads'

![Create_Issue](https://github.com/GitWorkshopWWCDSPracticeAccount/Git_Workshop/assets/128200371/363ad921-260a-440b-ba71-13cceec9296b)





**Task 2**

**Create a Pull Request**

All Squads: Clone the repository Git_Workshop using command  

``` git clone https://github.com/GitWorkshopWWCDSPracticeAccount/Git_Workshop.git ```

Squad 1:

1. Create a new code file using the commands navigating to the cloned directory
   
    ```
    $ echo print("Hello, Welcome to Git_Workshop Date: 29/09/2023") > Squad1_Bingo.py
    $ git add Squad_Bingo1.py
    $ git commit -m "Comments to commit: First file to commit from Squad 1"

    ```

   The output window looks as below:

   ![Commit](https://github.com/GitWorkshopWWCDSPracticeAccount/Git_Workshop/assets/128200371/bb962add-9063-47f8-bba9-26de5d208caa)

    
    ![Commit_task2](https://github.com/GitWorkshopWWCDSPracticeAccount/Git_Workshop/assets/128200371/7fc65de0-2991-4760-ac2a-49100fcc1e0f)

3. After commiting check the status using command ``` $ git status ```
   The output window should be as below
   ![Status_Commit](https://github.com/GitWorkshopWWCDSPracticeAccount/Git_Workshop/assets/128200371/aeb4000c-339b-451a-b2dc-52ce5edb6bcf)


4. Perform push operation to the original commit on the repository using the command ``` git push```
   or using the GitHub Desktop App 
   

Squad 2:  

1. Create a pull request to the main branch Git_Workshop to the branch "Test_Branch_for_Squads"
2. Fetch the file checked in by Squad 1 and modify changes to the file. example: print("I am a participant in Squad 2 - Meta") and enter comments.
3. Link the Issue created by Squad 2 to the pulled branch "Test_Branch_for_Squads"
4. Perform a commit and push to the Test_Branch_for_Squads
5. Now see the files changed and modification in the diff window
6. Assign to a member in Squad 3 (Squad Lead)

 ![diff-settings-menu_Github_Website](https://github.com/GitWorkshopWWCDSPracticeAccount/Git_Workshop/assets/128200371/70131299-a25b-4424-8e62-e90a616c5209)

Squad 3:

1. Reiew the files, enter comments and Approve to close the file.
2. Close the issue

Squad 4:

1. Push the changes to Main branch

     



**Task 3**

**Contribute to Project**

Squad 1 & Squad 2:

1. Create a new folder with a complete File Tree structure with your Team name as folder name example: "Squad1_Bingo"
   ![Tree Structure](https://github.com/GitWorkshopWWCDSPracticeAccount/Git_Workshop/assets/128200371/71312a59-d531-48dc-9001-b838d8f81ce8)
2. Commit and push the changes into the "Test_Branch_for_Squads"

Squad 3 & 4:

1. Merge the changes and commit the changes in to  main branch


   
    






**Disclaimer**: The contents are organized as per the Github's resources and from authorized training materials. The fiugres are from personal account.  

> :bulb:
**NOTE**
> This workshop is pepared to empower the Github skills to coders/non-coders.
> The contents are prepared based on the reference to the resources and materials available in the GitHub website. 
> Reprinting in any form is not permitted without the concern of the author.

> :no_entry:
**IMPORTANT**
> The team collaborators are responsible for their commits and the individual account takes no responsibility for illegal or unauthorized entry of information, data or commits performed by the collaborators.

> :warning:
**WARNING**
> Violating on the important information may lead to removal of your access from the team/repository
> Complaint may be filed against non conformity to code of conduct 
