<-- Hosting a static website using AWS-->
Resources:
 - AWS Console
 - AWS Amplify
 - GitHub
Implementation:
Confirm Build Settings -->
 - Create and initialize a repository.
 - Initialize git and push the application to the new GitHub repo executing the following commands in your command line interface.
    git init
    git remote add origin git@github.com:username/reponame.git
    git add .
    git commit -m “initial commit”
    git push origin master
 - If there is already a repo to connect, log in to the Amplify Console and choose Create new app at the middle of the page then Get Started under "Build your first app now".
 - Connect your GitHub repository. You also have the option of manually uploading your build artifacts without connecting a Git repository.
   After you authorize the Amplify Console, Amplify fetches an access token from the repository provider, but it doesn’t store the token on the AWS servers.
   Amplify accesses your repository using deploy keys installed in a specific repository only.
Save and Deploy -->
 - After you connect the repository service provider, choose a repository, and then choose a corresponding branch to build and deploy.
