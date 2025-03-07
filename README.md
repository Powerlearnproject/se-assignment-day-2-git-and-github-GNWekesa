[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/8wgCKhpZ)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=18458538&assignment_repo_type=AssignmentRepo)
# se-day-2-git-and-github
Q1
Version control is a system that tracks changes to files over time, allowing multiple people to collaborate on a project while maintaining a history of modifications. It helps developers work on different features simultaneously, revert to previous versions if needed, and prevent conflicts when integrating changes.
GitHub is widely used because it offers:
•	Cloud-based storage: Centralized hosting of repositories.
•	Collaboration tools: Supports pull requests, issues, and discussions for efficient teamwork.
•	Branching and merging: Enables parallel development without disrupting the main codebase.
•	Security and access control: Allows managing permissions for public and private repositories.
•	Continuous Integration/Deployment (CI/CD) integration: Automates testing and deployment processes.

Q2
To set up a new repository on GitHub, follow these steps:
1.	Log in to GitHub and click the "+" icon in the top-right corner, then select "New repository."
2.	Write a repository name.
3.	Add an optional description to explain the purpose of the repository.
4.	Leave the rest of options as they are
5.	Click "Create repository" to finalize the setup.

Q3
The README file is a GitHub repository that operates as a point of reference for users, contributors, and collaborators. It provides essential information about a project. It should involve a project title and description, installation instructions, usage guide, and contribution guidelines that offer clear information. The file offers effective collaboration that improves accessibility when writing code for various projects.
Q4
Public Repository
An open repository for documents is searchable and available to anyone with internet access for viewing. The repository is publicly accessible to anyone, but only contributors can directly modify the files there.
Advantages:
•	global participation – it allows input from multiple contributors, which makes it suitable for open-source projects.
•	greater reach – the project could gain exposure and may attract contributors, talent scouts, or employers.
•	version control for open projects – ensures changes and improvements made are recorded systematically.
•	accessibility – since public github is free of charge for open source projects, many people can work together on them without paying.
Disadvantages:
•	no privacy – the code is openly accessible, which may cause issues for sensitive or proprietary work.
•	limited control over use – people may take the code and use it inappropriately even if the code comes with a license.
•	spam & unwanted issues – due to high visibility, some public projects may attract spams or issues from unrelated people.
Private Repository
To reiterate, a private repository is a repository that can only be accessed by the owner and those that are explicitly permitted by the owner. It is not shared with other users and cannot be accessed by the public.
Advantages:
•	confidentiality & security – preserves the privacy of the code, essential for proprietary or sensitive projects.
•	confidentiality & security – access to the documents or files is restricted to the team members, minimizing interference from non-team members.
•	intellectual property protection – aids in preserving trade secrets and internal business logics.
Disadvantages:
•	limited community contributions – restricts open-source collaboration and public contributions.
•	free version has limitations for large teams – although you can use github to create private repositories for free, some of the functionality such as enterprise security and analytics will cost a lot of money.
•	less visibility – the project will be less visible, which poses a problem when searching for contributors or jobs.
Q5
Step 1- open Visual studio code software
Step 2 – go to file, select open folder and pick a folder where to write code
Step 3 – create a new python file with .py extension
Step 4- Go to view option on the menu bar, select terminal
Step 5 – type git init to initialize git
Step 6 – type git add . to add all files
Step 7 – type git commit –m, “a message”
Step 8 – type git remote add origin https…
The …. Section is for my repository url
Step 9 – type git push –u orgin master
A commit in Git is a recorded snapshot of the project's changes at a particular point in time.
Q6
Branching in Git allows developers to create separate versions (branches) of a project to work on new features, bug fixes, or experiments without affecting the main codebase.  To branch, below commands are used.
git init  
git remote add origin https://github.com/your-username/your-repo.git  
git checkout -b feature-branch  
git add .  
git commit -m "Added a new feature"  
git push -u origin feature-branch  
git checkout main  
git pull origin main  
git merge feature-branch  
git branch -d feature-branch  
git push origin --delete feature-branch
Q7
A pull request (PR) is a feature in GitHub that allows developers to propose, review, and discuss changes before merging them into the main branch.
git checkout -b feature-branch  
git add .  
git commit -m "Implemented new feature"  
git push -u origin feature-branch  
git add .  
git commit -m "Fixed requested changes"  
git push origin feature-branch  
git branch -d feature-branch  
git push origin --delete feature-branch  
Q8
Forking is the process of creating a personal copy of another user's GitHub repository under your own account. This allows modification of the project independently without affecting the original repository. The purpose of forking is to creates a copy under your GitHub account while the purpose of cloning is to create a local copy on your machine
Q9
GitHub Issues act as a task management system where teams can:
•	report bugs
•	suggest new features
•	discuss project improvements
•	assign tasks to team members
For example, a developer finds a bug in a website. They create an issue, describe the problem, assign it to a team member, and set a priority label.
Q10
Common challenges 
•	not using branches properly – making changes directly to main instead of using feature branches.
•	merge conflicts – editing the same file as someone else without pulling the latest changes.
•	forgetting to commit often – large, unclear commits make it harder to track progress.
•	ignoring .gitignore – accidentally pushing sensitive files 
•	not syncing with remote – working on outdated code without pulling the latest updates.
Best Practices to Overcome These Challenges
use feature branches.
commit frequently with clear messages 
pull before pushing 
use .gitignore 
review code via pull requests 
