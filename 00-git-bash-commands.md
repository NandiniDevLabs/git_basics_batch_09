# Git Bash Commands

To manage file and directories in Git Bash, use the following commands.

1. List files and directories
    ```
    ls
    ```
    >Lists files and directories in the current directory.
    
    ```
    ls -R
    ```
    >Lists contents of the current directory as well as every subdirectory within it

2. Change directory
    
    ```
    cd <DIRECTORY_NAME>
    ```
    >Navigates to a specified directory.

    ```
    cd ..
    ```
    >Navigates to parent directory.

3. Show current working directory
    ```
    pwd
    ```
    >Prints the current directory path.

4. Make a new file
    ```
    touch <FILE_NAME>
    ```
    >Creates a new empty file.

5. Remove a file
    ```
    rm <FILE_NAME>
    ```
    >Deletes a specified file.

6. Create a directory
    ```
    mkdir <DIRECTORY_NAME>
    ```
    >Creates a new directory.

7. Remove a directory
    ```
    rm -r <DIRECTORY_NAME>
    ```
    >Deletes a specified directory and its contents.

8. Copy files
    ```
    cp <SOURCE> <DESTINATION>
    ```
    >Copies a file or directory to a new location.

9. Move or rename files
    ```
    mv <SOURCE> <DESTINATION>
    ```
    >Moves or renames files or directories.

10. View the contents of a file
    ```
    cat <FILE_NAME>
    ```
    >Displays the content of a file in the terminal.

11. View file contents with paging
    ```
    less <FILE_NAME>
    ```
    >Opens a file in "less," allowing you to scroll through it.

12. View the beginning of a file
    ```
    head <FILE_NAME>
    ```
    >Displays the first few lines of a file.

13. View the end of a file
    ```
    tail <FILE_NAME>
    ```
    >Displays the last few lines of a file.

13. Search for a specific text within a file
    ```
    grep <PATTERN> <FILE_NAME>
    ```
    >Searches for a specific string in a file.

14. Search for a pattern in files across directories
    ```
    grep -r <PATTERN> <DIRECTORY>
    ```
    >Searches for a string in files within the specified directory and subdirectories.


## Clear Terminal
- **Shortcut** to clear terminal
    ```
    Ctrl + L
    ```
- Command to clear terminal
    ```
    clear
    ```

