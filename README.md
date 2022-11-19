create a new repository on the command line
echo "# Kushiembedded" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M Trail_01
git remote add origin https://github.com/Kushiembedded/Kushiembedded.git
git push -u origin Trail_01


or push an existing repository from the command line
git remote add origin https://github.com/Kushiembedded/Kushiembedded.git
git branch -M Trail_01
git push -u origin Trail_01

