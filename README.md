1. Create github repo
To create github repository through command line:
gh repo create project_numipie --public --source=. --push
2. Push the main branch
   git push --set-upstream origin main
3. Once the git repo is set up, to create a branch run the following command:
   git checkout -b  <branch_name>
4. Once checkedout then git init
   git init
5. Then run git add to add all the files:
   git add .
6. Run git commit with message -m
   git commit -m "your message"
7. Git push to push this new branch
   git push <branch_name> 
