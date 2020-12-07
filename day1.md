Today I have learned about how the internet works and basic command git

- [Git](https://www.beautiful.ai/player/-MKnNbA1PhusbO8ALVQn/FTW102-Git-and-Github)
- [Internet](https://www.beautiful.ai/player/-MKrfDomcrZMtVsJXWzQ/FTW101-Intro-Web)

Create a new repository
Git clone URL where I want to save
Create a file in the same directory
Push file to repo: 
   $ git add . # Adds the file to your local repository and stages it for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.
   $ git commit -m "Add existing file"
  # Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.
  $ git push origin your-branch (Eg: master)
  # Pushes the changes in your local repository up to the remote repository you specified as the origin

Pull from a Github repository:
  $ git pull remotename branchname
  # Grabs online updates and merges them with your local work
  
  -- git pull origin master


