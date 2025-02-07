# Sending local repository changes to remote

To send the changes of local repository to remote, use the following commands.

## Managing local repository changes
1. Check the status of changes
    ```
    git status
    ```
2. Add changes to staging
    - For single file
        ```
        git add <FILE_NAME>
        ```
    - For multiple files
        ```
        git add <FILE_NAME1> <CHILD_DIR/FILE_NAME2> <CHILD_DIR/GRANDCHILD_DIR/FILE_NAME3> 
        ```
    - For all files
        ```
        git add .
        ```
3. Commit changes to local repository
    ```
    git commit -m "COMMIT_MSG"
    ```


## Sending local changes to remote repository
1. Send changes from local to remote repo
    ```
    git push
    ```
