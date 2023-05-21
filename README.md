# E-waste

## Documentation:
https://docs.google.com/document/d/1OIJdZCdLKOf5cIfKrj5fF0_XHsAhc2p8As6oxp4ex7w/edit

## FIRST TASK FOR ALL: 
	
  ### Clone Repository: 
    git clone https://github.com/INSEES-Website/INSEES-2023.git

## EVERYTIME YOU WORK ON A NEW ISSUE:
### Pull the main
      git pull origin main 
      (ALWAYS DO THIS STEP TO AVOID ANY MERGE CONFLICTS)
### Make a new branch
	  git checkout -b yourinitials_branchname
			(eg: don_homescreenfooter)
### Add and commit
    git add .
    git commit -m “footer details added”
### Push
    git push --set-upstream origin don_homescreenfooter
    
##Or (If it not works then) 

### Push
    git remote -v
    git remote set-url origin <your fork repo link + SSH key> (like this https://desrdflnjdsklfmngjasdfjlsdkfj@github.com/INSEES-Website/INSEES-2023.git)
    git push origin <branchname>
