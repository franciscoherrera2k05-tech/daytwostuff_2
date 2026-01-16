*Normally you’d make a new codespace from a forked repo, but since you own this new one you cannot fork it. Additionally, you cannot make a new codespace from an empty repo. In order to make this new repo not empty, we clone it, push something, and then make a new codespace

Sign in to GitHub
Create a new repository
Download/Open VSCode
Click on “Clone Git Repository…” 
Enter the repository link and set the repository to a local destination
Open a new terminal
Create a new file titled nano requirements.txt and put in plotly version 6.5.1
Use this commands in this order:
git branch -M main
git add .
git commit -m “initial commit”
git push
Now that the repository is not empty, we can move on
Hit the “+” sign on the top right and click “New codespace”
Install the codespace extension
Click on the new “remote explorer” menu
Hover over the codespace with the same name as the new repository created, and then click the “connect to” button
You’re now connected to codespace and have a new working projection environment
