# Papier sur les environnements de modelisation collaboratifs

This files are LaTeX files for the dev. of the [WETICE'2011](http://www.sel.uniroma2.it/comets11/)	 paper.
Initiated by [JMB](mailto:bruel@irit.fr).

Usefull [git](http://git-scm.com/) command:

# start by copying a local copy of the repository
git clone git@github.com:jmbruel/wetice2011.git

# check result
git status

# setup your git info if not done already
git config --global user.name "Your Name"
git config --global user.email youremail@example.com

# create a branch for your own dev
git checkout -b mybranch
# check
git branch 

# work then
# commit your work locally
git commit -a -m "A message to indicate what you've done"

# merge with the main trunk if you believe it should
git checkout master # to check conflict
git merge mybranch  # if none
git push # the distant repository is now up to date