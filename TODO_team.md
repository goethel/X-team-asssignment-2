# X-Team Exercise #2 TODO as a team

This document describes what X-team members must together to complete X-Team Exercise #2.  

## 1. Create a shared GitHub repository __DO NOT FORK THIS REPOSITORY__

Only one team member completes this step.

  1. Login to GitHub with your wisc.edu GitHub account.
  2. Click the green [New Repository] link.
  3. Type the name suggested by GitHub for your newly created repository as your repository's name, ie.  your-repo-name
  4. Enter "cs400 X-Team NN" as the description for this new repository.  
  5. Replace NN with your X-Team number.
  6. Select Public.
  7. Click [Create repository].
  8. Scroll to bottom of Quick Setup page and click [Import Code].
  9. Enter this URL: https://github.com/cs400-deppeler/x-team-exercise-2
  9. Click [Begin Import] and wait for import to complete.
  10. Click the link to your newly created repository.
  11. Add Collaborators to your newly created repository.  
     a. Click Settings
     b. Click Collaborators
     c. For each member of your X-team
        i. Enter your team member's GitHub account username
        ii. Click Add Collaborator
        
  12. Share the name of this repository with all of your x-team members

## 2. Update rules.md collectively

All team members must help draft content and edit files.  
The rules.md file is where you will document the team rules you agree to.  
Please be sure to do the following for this document.

1. Replace NN in the top heading with your X-team's number.
2. Edit rules.md document the agreed upon rules for your X-team.

## 3. Draft a program proposal.md

All team members must help draft content and edit files.  
The proposal.md file is where you will document the program your team designs.
Please be sure to read and edit the proposal document via GitHub.
Each member should edit and commit to the proposal.
Answer the questions in the README.md file for your team.
It is reasonable to have each team member responsible for editing and answering at least one of the question answers.

## 4. Update your README.md file

Any team member may complete this step.

1. Replace the title (top line of the README.md file) with the name of your X-team's repository.
2. Answer the questions in the README.md file for your team.

## 5.a [optional] Create a local clone of your team's GitHub repository

Any and all team member's may create a local clone.

   1. Login to a CS Linux workstation
   2. cd ~/private
   3. mkdir cs400                         // if you do not already have this subdirectory
   4. mkdir cs400/xteam
   5. cd cs400/xteam
   6. git clone https://github.com/github-account-name/team-repo-name
   7. cd team-repo-name
   8. git remote -v                        // this shows that you are connected to your team's repo      

## 5.b [optional] Make and push a change from your local repository to your team's repository:

Any and all team member's may make edits in their local repository and commit to the team repository in this way.

   1. Complete step 7.a if you have not
   2. cd ~/private/cs400/xteam/team-repo-name
   3. git pull origin master                       // get all edits from team's GitHub repo
   4. edit the files locally
   5. git add .
   6. git commit -m "description of your edit"
   7. git push -u origin master                    // put all of your edits into team's GitHub repo


## 6. Submit your work

Submit these files to Canvas for your team for this assignment.   The final submission must contain all files in the same submission.

1. README.md
2. rules.md
3. proposal.md
  
  
