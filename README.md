5. Using mern-infrastructureto Create MERN-Stack Projects in the Future
Here's the process to create a new MERN-Stack project that starts with the infrastructure code:

Clone the mern-infrastructure repo: git clone <url of mern-infrastructure> <name-of-project>

Note that the folder created will be same as <name-of-project>instead of mern-infrastructure

1. cd <name-of-project>
2. Install the Node modules: npm i
3. Create a .env (touch .env) and add entries for DATABASE_URLand SECRET
4. Update the "name": "mern-infrastructure"in package.json to the name of your project.
5. Create a new repo on your personal GH account.
6. Copy the new GH repo's URL.
7. rm -rf .git
   git init
   git add .
   git commit -m 'first commit'
8. Update the remote's URL: git remote set-url origin <paste the copied GH url>
9. Push for the first time: git push -u origin main
10. Have fun coding your new project and don't forget to make frequent commits!