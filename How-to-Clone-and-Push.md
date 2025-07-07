# Cloning a GitHub Repo
## First Steps - Opening Location In VS Code
Open VS Code at location where you want to clone the repo

From Explorer:
> Navigate to desired location  
> Right click to open CMD  
> In CMD, type `code .`  
> DON'T FORGET THE `.`

---
## Second Steps - Clone the Repo
Copy the URL of the Repo you want to clone

Open VS Code Terminal and type the following:
> `git clone https://github.com/JordanWhitehead/Test-Repo.git`  
> *^ Don't forget to add .git at the end of the repo URL! ^*  
> `cd Test-Repo`  
> *^ Use the name of the repo directory here ^*  
> `code .`  

You have now navigated to a new VS Code window with the cloned GitHub repo

---
## Push Changes Made or New Files Added
> Use the following to add all changed files in the directory to the GitHub repository:  
> `git add .`  
> Commit Changes:  
> `git commit -m "Your commit message here"`  
> Push Changes:  
> `git push origin main`