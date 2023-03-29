Now that you have cloned a repo from github onto your machine it is time to learn about branching. When we work on new content we want to make sure that we are doing it in an isolated manner. Git Branching allows us to track what changes are made and why as well as permitting multiple people to be working on the same Repo. It is very simple concept. We clone the repo (stage 1) and then create a branch to edit (stage 2). Once we have edited it and are ready to push our changes to the dev server we merge (stage 3). The blow immage shows the main branch in purple, your branch in blue, and another dev working in the repo in yellow. 

<img src="https://i.imgur.com/4kFmY6Q.jpeg">

Step 1
- Open visual studio code
- Select the repo you have cloned, in this case GitWorkFlow
- Right Click GitWorkFlow
- Open integrated terminal
- Bottom of screen you will see the terminal
- Type git check -b yourname-Stage-2
- You will see "Switched to a new branch 'yourname-Stage-2'

Step 2
- Add a folder and files to your repo like you would for a personal dev server.
<img src="https://i.imgur.com/O35x3s0.jpeg">
- You should see the folder and files appear in the top left of visual studio code
- GitWorkFlow integrated terminal type git status
- It should show the added folder in red text
- GitWorkFlow integrated terminal type git add .
- This has now "saved" the changes you made to your branch
- GitWorkFlow integrated terminal type git status
- We now see our folder and all files within are green, ready to commit

Step 3
- GitWorkFlow integrated terminal type git commit -m "title of commit" -m "description of commit"
- When it comes to titling try and be specific so in my example I would type: git commit -m "Updating Minismg" -m "Changed meta values for the minismg aka uzi"
- Now lets check our changes on main vs yourname-Stage-2
- GitWorkFlow integrated terminal type git branch 
- The branch title in green is your active branch

You are now ready to push up to github which is stage 3. If you ever make any mistakes with git add or git commit you can type git reset to rollback your changes. If you ever get completely mixed up don't be afraid to restart or refer to this guide: https://docs.gitlab.com/ee/topics/git/numerous_undo_possibilities_in_git/ I would recommend not using stash at a beginner. 