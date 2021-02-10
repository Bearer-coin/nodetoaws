	Good article on deploying a Node.js app to AWS
	- Node.js Deploy to Amazon Web Services (AWS) Tutorial (Elastic Beanstalk, Express, Git, CI/CD)
	- https://www.youtube.com/watch?v=b0g-FJ5Zbb8

mkdir nodetoaws
cd .\nodetoaws
npm init --yes
npm install express
npm install mongodb
npm install -g nodemon
nodemon app.js
http://localhost:3000/

AWS account
https://us-east-2.console.aws.amazon.com/console/home?region=us-east-2#
ted@tedmurph.com / Pass4Aws

Developer tools -> code pipeline

used the bearer-coin github account
	https://github.com/Bearer-coin/version-0.1
	ted@bearer-coin.com / Pass4Github

need to create a github repository for our project

echo "# nodetoaws" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Bearer-coin/nodetoaws.git
git push -u origin main

actually said:

git init
npx gitignore node
git status

PS C:\Projects\CryptoCurrency\Bearer-Coin\nodetoaws> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        app.js
        package-lock.json
        package.json

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Projects\CryptoCurrency\Bearer-Coin\nodetoaws>

now, do:

git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Bearer-coin/nodetoaws.git
git push -u origin main

