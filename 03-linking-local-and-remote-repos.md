# Linking local and remote repositories

To connect local and remote repositories, use the following commands.

1. Add remote repository 
    ```
    git remote add origin <GITHUB_REPO_URL>
    ```
    ><u>**Note:**</u> Remote repo is more generally referred as `origin`, however you can replace it with any other name in the above command.

2. Check the connection with remote repository
    ```
    git remote -v
    ```
    ><u>**Note:**</u> If remote repo is not linked to local, there will be no output from this command.