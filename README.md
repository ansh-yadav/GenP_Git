# GenP_Git Git Commands

- Cloning the repo to local directory 
  - `git clone https://github.com/JiyaVe/GenP_task.git`
  


- Creating own repo and cloning as above
  - `git clone https://github.com/ansh-yadav/GenP_Git.git`
  - Created this repo with .gitignore and readme.md file and then clone this
  - Copy Pasted filed from GenP_task -> GenP_Git

- Staging and commit the new files locally
  - `git add .`
  - `git commit -m "Intializing Unity Task"`


- Creating New branch
  - `git branch task`

- Checking out to new branch
  - `git checkout task`

  - Done the Unity 3D scene work

- Again staging and commiting
  - `git add .`
  - `git commit -m "My work in Branch Task"`

- Add remote origin if not added ( Mine says already exists as I think I clone from there)
  - `git remote add origin https://github.com/ansh-yadav/GenP_Git.git`

- Push main to remote by checking out in main
  - `git push -u -f origin main`    // -f denotes force means it overides the existing files 

- Push task to remote by checking out in task
  - `git push -u -f origin task`

- Check out to main and merge task to main
  - `git merge task`

- push main after merge
  - `git push -u origin main`
