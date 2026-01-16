*Normally you’d make a new codespace from a forked repo, but since you own this new one you cannot fork it. Additionally, you cannot make a new codespace from an empty repo. In order to make this new repo not empty, we clone it, push something, and then make a new codespace

1. Sign in to GitHub
2. Create a new repository
3. Download/Open VSCode
4. Click on “Clone Git Repository…” 
5. Enter the repository link and set the repository to a local destination
6. Open a new terminal
7. Create a new file titled nano requirements.txt and put in plotly version 6.5.1
8. Use this commands in this order:
     a. git branch -M main
     b. git add .
     c. git commit -m “initial commit”
     d. git push
   Now that the repository is not empty, we can move on
9. Hit the “+” sign on the top right and click “New codespace”
10. Install the codespace extension
11. Click on the new “remote explorer” menu
12. Hover over the codespace with the same name as the new repository created, and then click the “connect to” button
13. You’re now connected to codespace and have a new working projection environment
