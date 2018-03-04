Åcor create a new repository on the command line

echo "# testblog" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:FrankRx41/testblog.git
git push -u origin master
Åcor push an existing repository from the command line

git remote add origin git@github.com:FrankRx41/testblog.git
git push -u origin master
Åcor import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.