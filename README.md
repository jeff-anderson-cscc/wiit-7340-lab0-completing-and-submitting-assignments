# Completing and Submitting Coding Assignments Lab

A video walk-through of this process entitled, *Process for Completing
and Submitting Coding Assignments*, is available in Blackboard under Java IV ->
Course Information or through [this link](https://1drv.ms/v/s!AsY74JxXap277EbuW6luuDWSopi-).  

# Instructions

## 1. Create a private repository for your your work:

1. If necessary, login to your personal GitHub account
1. Visit the following URL to create a personal repository based on the base template: [https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments/generate](https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments/generate)
1. Enter ``lab0-completing-and-submitting-assignments`` for the repository name
1. **Important:** Click "Private" to keep others from viewing your work
1. Click "Create repository from template"

Once the repository is created, GitHub will display the Code tab and you should see this content. 

## 2. Add me as a collaborator so I can view and grade your work:

1. Click on the "Setting" tab
1. Choose "Collaborators" from the left navigation
1. If prompted, reenter your GitHub password
1. Enter ``jeff-anderson-cscc`` in the "Search by username" field then click "Add collaborator"

Once you add me, you should see my name and picture in the "Collaborators" section at the top of the page and the bottom of the page should show, "1 of 3 collaborators".

## Create and checkout a new project for this lab in IntelliJ

1. Click on the "Code" tab on your GitHub repository page
1. Click the green "Clone or Download" button above in this repository
1. Copy the repository URL to your clipboard
1. If necessary, open IntelliJ IDEA via "Applications" -> "Programming" -> "IntelliJ IDEA Community Edition"
1. If a previous project comes up, choose "file" -> "Close project"
1. In the Welcome screen, choose "Checkout from version control"
1. Choose "Git"
1. Paste the URL you copied in step 2 into the "Clone Repository" dialog URL field
1. Review and, if you wish, change the location in the "Directory" field to something like ``/home/your-user-name-here/java-iv-labs/lab0-completing-and-submitting-assignments`` where "your-user-name-here" is the username you use to login to workspaces which, for me, is "janderson141" so my directory is: ``/home/janderson141/java-iv-labs/lab0-completing-and-submitting-assignments``
1. Click "Clone" to clone your repository
1. If prompted, enter your GitHub user name and password
1. If you get an, "Unlock Keyring" dialog, enter the password you use to login to AWS Workspaces
1. In the "Checkout From Version Control" dialog, click "Yes"
1. If necessary, expand the project by clicking on, "1. Project" from the left margin of the IntelliJ workspace

## Before you start Coding

1. Go to "VCS" then choose "Git" -> "Branches"
1. Click on "+ New Branch"
1. Give it a meaningful name like "changes-for-lab"
1. Making sure "Checkout Branch" **is** checked, click OK.

## Complete the coding assignment as directed, committing your changes frequently

1. For this lab, replace "World" in "Hello World" with your name in ``HomeController.java`` under ``src/main/java/hello``
1. Test your changes:
    1. From the "Project" pane, right click on ``Application`` under ``src/main/java/hello`` 
    1. Choose "Run 'Application.main()"
    1. When you see ``hello.Application                        : Started Application`` in the Application Run window, open a new tab in your browser and visit [localhost:8080](localhost:8080)
    1. If the page displays with the message "Hello" along with your name, you have successfully tested your changes. 
1. From the "VCS" menu, choose "Commit"
1. Enter a meaningful comment like, "updated Home Controller to display my name", in the "Commit Changes" dialog then press "Commit"


## Push your changes and create a pull request for grading grading

1. Make your final commit if you haven't already (see last step in the section above)
1. From the "VCS" menu, choose "Git" then "Push"
1. Click "Push" in the "Push Commits" dialog
1. If prompted, enter your GitHub password and press "Log In"
1. You should see a "Push Successful" message in the bottom right corner of IntelliJ
1. if necessary, log into GitHub and navigate to your repository
1. Click on "branches" and locate your work branch in the listing
1. Click on the green "Open" pull request button to the right side of the branch forName
1. Enter a meaningful comment like, "ready for grading", in the "Open a Pull Request" screen
1. Click on the "Create Pull Request" button
1. **Important"** under "Reviewers" in the right navigation, click "Request" next to my name so I get an email asking for my review

## Wait until I review your pull request

Your work will be considered on time or not based on commit timestamps in GitHub. To avoid having to resubmit your work in Blackboard, **wait until I review and approve** your pull request in GitHub before moving on to the next step.

## Once your pull request is reviewed and approved

While GitHub is used for reviewing and grading your work, Columbus State needs an audit trail to show you have successfully completed the assignment. This step is also necessary to be assigned an official grade for your work. 

1. Using the file explorer under "Places", navigate to the parent directory of where you created your IntelliJ project
1. Right click on the project folder name then choose "Compress"
1. **Important:** Choose ".zip" for the file format
1. Press "Create"
1. If necessary, Login to Blackboard
1. Navigate to the assignment in Blackboard
1. Under "assignment Submission", choose "Write Submission"
1. Paste a link to your GitHub repository pull request in the editor field
1. Click "Browse My Computer" in the "Attach Files" section choosing the ZIP files you just created
1. Click "Submit" and follow all Blackboard instructions to complete the submission process

## Getting help

First, carefully read the directions above. It's easy to skip a step then run into problems later. If you are still stuck, send me an email via blackboard with details of your problem. 

Another excellent way to solicit my help is to follow the procedures in the *push your changes and create a pull request for grading grading* section above. Add me as a reviewer then add a comment with details of how I can help. The advantage of this approach is I can see your code and provide more accurate guidance. If you do this, there is no need to create a new pull request for grading when you are done.  Simply commit all your changes and push them to GitHub then add a comment asking for a final review. 
