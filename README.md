GitHub & GitLab Collaboration and Workflow Setup (Practical Assignment)


Project Overview

This practical assignment demonstrates my understanding of Git, GitHub, and GitLab workflows used in DevOps teams.
The goal of this task was to perform repository setup, branching, collaboration workflow using Pull Requests, GitLab repository setup using SSH, repository mirroring between GitLab and GitHub, and access control using roles.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Objective:

To ensure smooth development workflow and collaboration between GitHub and GitLab by performing:

1.Repository creation (public + private)
2.Local development and branch management
3.Pull request workflow (dev → main)
4.GitLab private repo setup using SSH
5.GitHub ↔ GitLab repository mirroring
6.GitLab access control with roles (Guest → Developer)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🛠 Tools & Technologies Used

Git
GitHub
GitLab
SSH Authentication
Repository Mirroring
Branching & Pull Requests
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Part 1: Github Task

1️⃣ Repository Setup

  Create two repositories on GitHub:
  
     One public
     
     One private
   
![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task1%20public-repo.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task1%20private-repo%20(2).png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2️⃣ Local Development (Private Repo)

Steps performed:

   1.Cloned both repositories using HTTPS

   2.In private repo:

       Created a branch: dev

       Added files in Main Branch: index.html, readme.md

       Made at least two commits

       Pushed dev branch to GitHub

📸 Screenshots:

Clone Repositories

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task1%20public-clone.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task1%20public%20index.html.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task1%20private%20index.html.png)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
3️⃣ Collaboration Workflow

 Steps performed:

     1.Created a Pull Request to merge main → dev
  
     2.Reviewed and merged the PR
  
     3.Verified changes in dev branch
  
📸 Screenshots:

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task1%20public%20main-branch.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task1%20public%20dev%20branch.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task1n%20priavte%20main%20branch.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task1%20private%20dev%20branch.png)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Part 2: GitLab Tasks

4️⃣ GitLab Repository Setup

   Steps performed:

     1.Created a private repository on GitLab
  
     2.Cloned it using SSH (not HTTPS)
  
     3.SSH Token
  
     4.Created project structure:
  
         src/app.py
      
         docs/guide.md

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task2%20gitlab-mirror.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task2%20github-mirror.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task2%20gitlab%20mirroring.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task2%20add-%20mirroring.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task2%20cmd%20to%20create%202%20dir.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task2%20create%202%20dir%20mirror.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task2%20display%20mirror%20changes%20on%20gitlab.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task2%20gitlabbb%20mirr.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task2%20githubbb%20mirr.png)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
6️⃣ Access Control 

Steps performed:

    1.Invited a friend to GitLab repository
   
    2.Assigned role as Guest

    3.Then change their role to Developer, and let them push one file
   
![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task2%20access-control.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task2%20access-control-guest.png)

![image alt](https://github.com/poojagaikwad19/Github-Gitlab-practical-test/blob/main/task2%20access-control%20change%20role%20from%20guest%20to%20devloper.png)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
✅Final Outcome


At the end of this practical assignment, successful collaboration workflows were established on both GitHub and GitLab. Repositories were properly created and managed, branching and pull request workflows were implemented, and access control was configured using role-based permissions. Repository mirroring between GitLab and GitHub was successfully set up, ensuring automatic synchronization of changes across platforms.






