## push to github
1. change/add remote to github repo | git remote add github https://github.com/username/project-name.git
2. push to origin | git push github --all
3. go to main repo | https://github.com/BreadstickoSaurus/CollectionPlatform
```
cd projectname

# Initialize the main repository
git init

# Add submodules for each repository
git submodule add https://github.com/your-github-username/projectname/Documentation.git documentation
git submodule add https://github.com/your-github-username/projectname/frontend.git code/frontend
git submodule add https://github.com/your-github-username/projectname/backend.git code/backend
git submodule add https://github.com/your-github-username/projectname/data.git code/data
git submodule add https://github.com/your-github-username/projectname/docker.git docker

# Commit and push the main project
git add .
git commit -m "Add repositories as submodules"
git push -u origin main
```