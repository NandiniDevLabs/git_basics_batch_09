# Creating and Cloning repositories

To create a new local repository or clone remote repository to local, use the following commands.

## Creating new local repository.
1. Select a location and create a directory
    ```
	mkdir <REPO_NAME>
    ```
2. Navigate to newly created directory
    ``` 
	cd <REPO_NAME>
    ```
3. Check the status of current directory
    ```
	git status
    ```
    ><u>**Note:**</u> If current directory or its parent directory is not a git repository, the response will be `fatal: not a git repository`. This is the expected output, to proceed further. 
4. Create local Repository
    ```
	git init
    ```
5. Verify local repository
    ```
	git status
    ```

## Cloning remote repository to local
1. Clone remote repo
    ```
    git clone <GITHUB_REPO_URL>
    ```
    ><u>**Note:**</u> In case of errors, hit the GitHub remote repository link directly. If access permissions are granted, repo will be accessible.

