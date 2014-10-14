git tutorial
============

Prev. Configuration
-------------------

   git config --global user.name <my name>
   git config --global user.email <my_email>
   git config --global color.ui auto # Colors!

Clone the repository via SSH
----------------------------
   mkdir Repositories && cd $_
   git clone git@github.com:TIDCampus/git-tutorial.git
   cd git-tutorial
   
Create custom branch
--------------------
   git branch <name>
   git checkout <name>
   touch profiles/<name>_profile.md
   # Add information
   git add <name>_profile.md
   git commit -m "My first commit with my profile"
   
Share your commit
-----------------
   git push origin <my_branch>   