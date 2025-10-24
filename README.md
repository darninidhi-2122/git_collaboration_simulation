# git_collaboration_simulation

Task7: Git Collaboration Simulation
•	Create a new repo on GitHub and clone it locally.
•	Create a branch feature/api.
•	Make some commits, push to GitHub, and open a Pull Request (PR).
•	Merge the PR using GitHub UI.
•	Pull changes back to your local repo and verify.
•	Share link to the PR and output of git branch -a.

steps to be followed
1. Create a new GitHub repo
 --> Go to https://github.com/new
 --> Name the repo: git_collaboration_simulation
 --> Choose Public, and check “Add a README file”.
 --> Click Create Repository.

2. Clone it locally
 --> git clone https://github.com/darninidhi-2122/git_collaboration_simulation.git
 --> cd git_collaboration_simulation
 --> Verify: git remote -v

3. Create a new branch
 --> git checkout -b feature/api

4. Make some commits
 --> Create a new file:
 --> echo "This is API development feature" > api.txt
 --> Add and commit: git add api.txt and git commit -m "Add initial API feature file"
 --> Make another small change:
 --> echo "Added endpoints for user data" >> api.txt
 --> git add api.txt
 --> git commit -m "Add user data endpoint details"

5. Push branch to GitHub
 --> git push origin feature/api

6. Open a Pull Request
 --> Go to your repo on GitHub.
 -->You’ll see a banner: “Compare & pull request” → Click it.
 --> Add a title like: "Add API feature branch changes".
 -->Create the PR.
 -->Merge it using “Merge pull request” → “Confirm merge” in the GitHub UI.

7. Pull changes to local repo
 --> Back in your local terminal:
 --> git checkout main
 --> git pull origin main
 --> Verify merge: cat api.txt
 --> You should see both lines you added earlier.

8.Check branches
 --> git branch -a

9. Share links and output:
 --> You need to share:
 -->PR Link – from GitHub (e.g. https://github.com/<your-username>/git_collaboration_demo/pull/1)
 -->Output of git branch -a (copy-paste from your terminal).
 --> output PR link - https://github.com/darninidhi-2122/git_collaboration_simulation/pull/1
   feature/api
  * main
  remotes/origin/HEAD -> origin/main
  remotes/origin/feature/api
  remotes/origin/main

