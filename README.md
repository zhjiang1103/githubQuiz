## Week 14 Quiz - Debugging, Git, & GitHub

You have just joined your favorite company and have been tasked with printing new data to a webpage. However, the existing files/directories are all jumbled up, and the code seems to have errors. Fix the bugs and sile structure. 

##1. Debug the broken code so that it's working

![App Screenshot](<screenshot1.png>)

##2. Correct the file architecture using command line
```bash
git mv client/server/ ./server
```
##3. node_modules are committed, remove them from repo on GitHub
```bash
# Add node_modules to .gitignore (dependencies section)
echo '**/node_modules' >> .gitignore

# Remove node_modules folder from the git repo and remote
cd client
git rm -r --cached node_modules
git add .


# Add node_modules to .gitignore (dependencies section)
echo '**/node_modules' >> .gitignore

# Remove node_modules folder from the git repo and remote
cd server
git rm -r --cached node_modules
git add .
```

##4. Correct the server file’s directory by moving it to the appropriate directory
```bash
git mv client/server/ ./server
```
##5. Update README with
    - screenshot of the app's webpage
    ![App Screenshot](<screenshot2.png>)
   