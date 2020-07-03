# friday-exercise
A repo for Generation JWD students to practise working with git and github

Git and GitHub exercise

Create your account in GitHub and log in
Access Michael’s repository from the link below
    https://github.com/mahearn/friday-exercise

Fork his repository on GitHub. Use the  button - top right
In your Terminal, create a new folder called gen2
    mkdir gen2

Move into the folder 
    cd gen2

From the terminal , clone the forked directory from GitHub within the gen2 folder
    git clone https://github.com/{username}/friday-exercise

Move into the cloned directory
cd friday-exercise

List the contents of the directory
     ls -al

Create a directory called images inside the friday-exercise directory
mkdir images

Add your image file in the images directory in Finder/Folder explorer

From the terminal, create a new file in your forked directory in the master branch and name it yournameprofile.html

touch lavinaprofile.html

Edit the file yournameprofile.html in vscode and save the file (Edit your name, image and description) - see file code at the end of the page

Check the status of the directory
     git status

Add the new file to the staging area
      git add .

Commit the changes to the master repo
    git commit -m "Edited my profile details"
  
git status 
 You will see the SHA for your new HEAD of your branch.

Push the file into the forked Github master repo
     git push

Go to GitHub and create a pull request from Michael’s repo

Michael will review your pull request and merge your files to his master 

Before making any more changes to your forked repo, make sure you use the 
git pull  command to stay in synch with the GitHub repo

_______________________________________________________________________________
<!DOCTYPE HTML>
<html>
 <head>
   <meta charset = "utf-8">
   <title>My Profile</title>
  
 </head>
 <body>
     <p>My Profile: Lavina R Lobo</p>
   <img src="images/lavinaimg.png">
   <p> Lavina believes mindfulness in the workplace is key to success - <br/>
     she lives out through her interests in yoga, meditation, gardening, and painting. <br/>
     She is currently working as an instructor and is always interested in new challenges</p>
   <footer>
   </footer>
 </body>
</html>
 
 

