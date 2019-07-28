# Hotel-App-Using-Cassandra
Sample Hotel Application created by using Cassandra as the backend database


## Git Usage Instructions

### First time usage

git clone https://github.com/Sahil-Ajmera/Hotel-App-Using-Cassandra.git

git checkout -b "YOUR-NEW-BRANCH-NAME" ((This branch will made off master branch so make sure master is updated. If your file did not get changed by master update, ignore this))

### To get latest code on master branch

git checkout master

git pull

### To commit code locally to your branch after you have made a change

git add --all 

git commit -m "Change 1 made((Do not copy this string, this is my own :P))"

Do  some work . . . Add comments too

git add --all

git commit -m "Added some unvisible buttons"

Do  some work . . . Add comments too

git add --all

git commit -m "Updated x and added code for y functionality"

....
...


### To push code to github

After you have made some changes you can push your branch to git

git push origin YOUR-NEW-BRANCH-NAME

### After pushing code to github

Go to repo online

Click Compare and add pull request option

"Add some description with output screenshots if possible"

Click add pull request option

Search for reviewers on page (Ctrl + F)

Add reviewers

Inform reviewers and wait and sip coffee till then. :D

### For reviewers

Check repo when informed

Understand code logic and try to update your code and test if it works for you

Approve/Reject based on working and code with comments 

### To Test someone else's pull requst on your local
Follow this link:
https://help.github.com/en/articles/checking-out-pull-requests-locally

## Getting Started

### Download or clone project
git clone https://github.com/Sahil-Ajmera/Hotel-App-Using-Cassandra.git

### Change Cassandra Configs in Cassandra installation
Make changes to seed, listen and rpc address in the cassandra.yaml file to the address on which data will be replicated. Cassandra.yaml file lives in CassandraInstallationPath/conf/cassandra.yaml
