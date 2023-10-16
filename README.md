## Week 14 Quiz - Debugging, Git, & GitHub

You have just joined your favorite company and have been tasked with printing new data to a webpage. However, the existing files/directories are all jumbled up, and the code seems to have errors. Fix the bugs and sile structure. 

1. Debug the broken code so that it's working
![Alt text](<Screen Shot 2023-10-16 at 9.17.32 AM.png>)
2. Correct the file architecture using command line
git mv client/server/ ./server

3. node_modules are committed, remove them from repo on GitHub
cd client
//Adding node_modules to .gitignore dependencies section
**/node_modules
//Remove node_modules folder from the git repo and remote
git rm -r --cached node_modules
git add .

cd server
//Adding node_modules to .gitignore dependencies section
**/node_modules
//Remove node_modules folder from the git repo and remote
git rm -r --cached node_modules
git add .
4. Correct the server file’s directory by moving it to the appropriate directory
git mv client/server/ ./server
5. Update README with
    - screenshot of the app's webpage
    ![Alt text](<Screen Shot 2023-10-16 at 9.14.21 AM.png>)
   