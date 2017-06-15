## Resources used
- [GitHub](https://github.com)
- [Cloud9](https://c9.io/)

## Getting set up

### On GitHub
1. Sign up for a GitHub account [here](https://github.com). 
2. Leave this window open as you will need to perform further set up actions to integrate smoothly with Cloud9.

### Setting up SSH between Github and Cloud9
3. If you have registered to attend the workshop, you should receive an email notifying you to sign up for an account on Cloud9. If you did not receive the invite, please alert us at the workshop. If you _did not_ register for the workshop, you may create an account on Cloud9 too. (The difference is that you'll need a credit card if you're creating an account yourself.)
4. Go to https://c9.io/ to sign up for a Cloud9 account by clicking on the GitHub icon in the top right corner. You will need to authorize Cloud9 to use your Github account.
5. Once it's done, you will be at the Dashboard page.
6. Go to `https://c9.io/account/ssh` to access your SSH Settings page.
7. Open another window and go to `https://github.com/settings/keys` to access your SSH and GPG keys on Github.
8. Click on the green New SSH key button in the top right corner.
9. Enter "Cloud9 IDE" in the Title field.
10. Switch back to the SSH Settings page in the previous window and copy everything in the grey box. Paste the contents in the Key field on your SSH and GPG keys page on Github.
11. Click on the green Add SSH key button.

### On Cloud9
12. Click on Create New Workspace.
13. Enter a name for your workspace and a brief description.
14. Select Ruby on Rails for the Choose a template option.
15. Click on the green Create Workspace button to proceed.
16. You should see a loading window, and this may take a while, so keep the window open and let it run. Please try this at home. 
17. When things are set up, you should see your workspace, with a file manager in the left column, a text editor taking up most of the space in the main right area and a smaller terminal in the bottom of the right area.
