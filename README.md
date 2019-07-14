# Completing and Submitting Coding Assignments Lab

**Note:** A video walk-through of this assignment entitled, *Process for Completing and Submitting Coding Assignments*, is available in Blackboard under Java IV Programming -> Our Classroom -> Before you begin.

# Instructions

## 1. Create a private repository for your your work:

Normally, everyone on a team works off a shared repository that functions as the hub for collaboration and communication. In a classroom setting, you will need to keep your work private to prevent others from unfairly benefiting from your awesomeness. In this step you will create a private GitHub repository from a base template which I provide.

1. If necessary, login to your personal GitHub account
1. Visit the following URL to create a personal repository based on the base template: [https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments/generate](https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments/generate) 
1. Enter ``lab0-completing-and-submitting-assignments`` for the repository name
1. **Important:** Click "Private" to keep others from viewing your work
1. Click "Create repository from template"

Once the repository is created, GitHub will display the Code tab and you should see this content. Note that in future labs, the URL in step 2 and the repository name you provide in step 3 will vary.

## Add me as a collaborator so I can view and grade your work:

In this step, your team of one will become a team of two so I can view your code, answer questions, and grade your work.

1. From your repository, click on the "Setting" tab
1. Choose "Collaborators" from the left navigation
1. If prompted, reenter your GitHub password
1. Enter ``jeff-anderson-cscc`` in the "Search by username" field then click "Add collaborator"

Once you add me, you should see my name and picture in the "Collaborators" section at the top of the page and the bottom of the page should show, "1 of 3 collaborators".

## Create and checkout a new project for this lab in IntelliJ

In this step, you will create a new project in IntelliJ by checking out the code in your newly created GitHub repository.

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
1. If necessary, expand the project pane by clicking on, "1. Project" from the left margin of the IntelliJ workspace

## IMPORTANT: Before you start coding

It is important to never directly commit to the "master" branch. Instead, always create a new branch for each assignment. Failure to do so will prevent you from creating a pull request for grading.

1. Go to "VCS" then choose "Git" -> "Branches"
1. Click on "+ New Branch"
1. Give it a meaningful name like, "changes-for-lab"
1. Making sure "Checkout Branch" **is** checked, click OK.

## Complete the coding assignment as directed, committing your changes frequently

This lab is pretty basic. You will make one change in one file so I can verify you are successfully able to create a pull request for grading. In other labs, this section will vary.

1. For this lab, replace "World" in "Hello World" with your name in ``HomeController.java`` under ``src/main/java/hello``
1. Test your changes:
    1. From the "Project" pane, right click on ``Application`` under ``src/main/java/hello`` 
    1. Choose "Run 'Application.main()"
    1. When you see ``hello.Application : Started Application`` in the Application Run window, open a new tab in your browser and visit [localhost:8080](localhost:8080)
    1. If the page displays with the message "Hello" along with your name, you have successfully tested your changes. If it still says, "Hello World", make sure you saved your changes then stop and rerun the application. If you are unable to run your application due to a missing JDK, see Blackboard for instructions on how to fix this. 
1. From the "VCS" menu, choose "Commit"
1. Enter a meaningful comment like, "Updated Home Controller to display my name", in the "Commit Changes" dialog then press "Commit" (or "Commit and Push" followed by "Push" which has the added benefit of backing up your work in GitHub)

## Push your changes and create a pull request for grading

Once you have successfully completed the assignment, follow this process to create a new pull request and add me as a reviewer so I can grade your work.

1. Make your final commit if you haven't already (see last step in the section above)
1. If your most recent commit hasn't been pushed to GitHub:
    1. Choose "Git" then "Push" from the "VCS" menu.
    1. Click "Push" in the "Push Commits" dialog
    1. If prompted, enter your GitHub password and press "Log In"
    1. You should see a "Push Successful" message in the bottom right corner of IntelliJ
1. If necessary, log into GitHub and navigate to your repository
1. Click on "branches" and locate your work branch in the listing
1. Click on the green "Open" pull request button to the right side of the branch forName
1. Enter a meaningful comment like, "ready for grading", in the "Open a Pull Request" screen
1. Click on the "Create Pull Request" button
1. **Important"** under "Reviewers" in the right navigation, click "Request" next to my name so I get an email asking for my review

## Wait until I review your pull request

Your work will be considered on time or not based on commit timestamps in GitHub. To avoid having to resubmit your work in Blackboard, **wait until I review and approve** your pull request in GitHub before submitting your assignment in Blackboard.

**NOTE:** If I request additional changes, commit them to your working branch and push them to GitHub which will automatically add them to your pull request. When you are ready for a re-review, add a comment to your pull request asking me to do so. 

## Once your pull request is reviewed and approved

While GitHub is used for reviewing and grading your work, Columbus State needs an audit trail to show you have successfully completed the assignment. This step is also necessary to be given your official grade in Blackboard. 

From your AWS Workspace:

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

First, carefully read the directions above. It's easy to skip a step then run into problems later. Second, the videos in each module are your best source of information needed to complete each assignment. While the actual code will vary, the videos take you through everything you need to be successful. 

Finally, if you are still stuck, send me an email via blackboard with details of your problem. Better yet, follow the procedures under [Push your changes and create a pull request for grading](#push-your-changes-and-create-a-pull-request-for-grading) section above. Add me as a reviewer then add a comment with details of how I can help. The advantage of this approach is I can see your code and provide more accurate guidance. 
