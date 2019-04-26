# Cloud-Computing

## Homework #1: Host a dynamic website using cloud virtualization

Use the below commands to clone the repo

echo "# Cloud-Computing" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/niteshvudutha/Cloud-Computing.git
git push -u origin master

Then use commands accordingly


### Usage of Application ###

I have developed a simple application which accepts two numbers. Then uses a GET request sends them to server, calculates the sum and returns

Steps :
1. Enter 2 numbers in given 2 input boxes
2. Click on Calculate button
3. Wait for the result to appear beside the label "SUM of both the numbers is ___"

What Happens when you click Calcuate Button

This request will be sent to an API gateway endpoint that triggers a Lamda function and gives you the response