# First_Charge
Repo for the First Charge car, meant to include the electrical schematics and kicad files

# Brief Github Command Tutorial for the Team by Kevin Sui
# To connect git with github website
  (1) $ ssh-keygen -t ed25519 -C "<insert your email here @gmail.com>"
  (2) When asked to "Enter file in which to save the key:" Press Enter for default
  (3) Add Passphrase to the ssh key if you give enough shits, else press enter for no passphrase
  (4) A ed25519 key randomart image is printed out. Look above and find location of public key "Your public key has been saved in /c/Users/racin/....." Go to that location $cd /c/Users/racin/...
  (5) To quickly see public key $ cat id_ed25519.pub 
  (6) Go to github website, go to First_Charge repo, Settings --> SSH key --> Add Key --> Copy the public key in
  (7) $ git clone "<insert HTTP link in here>' / $ git pull

# To use github
  (0) Use ls and cd to go to directory where you want to store git $ git init
  (1) git pull
  (2) git status

# To change git branches
  (1) To show current branches $ git branch
  (2) $ git checkout <branch to change to>
  (3) $ git branch -d <local branch to delete> 
  
# To push changes to a branch
  (1) $ git add .
  (2) $ git commit -m 'Message for commit, date, time'
  (3) $ git push
  (4) go one website and merge if no issues / overwritten stuff / etc
 
