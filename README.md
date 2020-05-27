URL => https://github.com/Sahu-Ayush/firstrepodir
#######################################################
HTTP => https://github.com/Sahu-Ayush/firstrepodir.git
SSH = > git@github.com:Sahu-Ayush/firstrepodir.git
#######################################################
…or create a new repository on the command line
echo "# firstrepodir" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Sahu-Ayush/firstrepodir.git
git push -u origin master
######################################################################
…or push an existing repository from the command line
git remote add origin https://github.com/Sahu-Ayush/firstrepodir.git
git push -u origin master
#####################################################################
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.



########################
git error: failed to push some refs to remote

Solution:

If the GitHub repo has seen new commits pushed to it, while you were working locally, I would advise using:
git pull --rebase origin master
git push origin master



