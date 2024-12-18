# Unix Commands List

This file contains the list of Unix commands used during the Unix Tutorial exercises, along with a brief explanation of each command and examples.

## Commands Used

### 1. Listing Files and Directories
- **Command**: `ls`
  - **Description**: Lists files and directories in the current working directory.
  - **Example**: 
    ```bash
    ls
    ```
- **Command**: `ls -a`
  - **Description**: Lists all files, including hidden files (those starting with a dot).
  - **Example**:
    ```bash
    ls -a
    ```

### 2. Making Directories
- **Command**: `mkdir <directory_name>`
  - **Description**: Creates a new directory with the specified name.
  - **Example**:
    ```bash
    mkdir unixstuff
    ```

### 3. Changing Directories
- **Command**: `cd <directory_name>`
  - **Description**: Changes the current working directory to the specified directory.
  - **Example**:
    ```bash
    cd unixstuff
    ```
- **Command**: `cd ..`
  - **Description**: Changes the current directory to the parent directory.
  - **Example**:
    ```bash
    cd ..
    ```
- **Command**: `cd`
  - **Description**: Changes the current directory to the home directory.
  - **Example**:
    ```bash
    cd
    ```

### 4. Displaying the Current Directory
- **Command**: `pwd`
  - **Description**: Prints the full path of the current working directory.
  - **Example**:
    ```bash
    pwd
    ```

### 5. Copying Files
- **Command**: `cp <source_file> <destination_file>`
  - **Description**: Copies the source file to the destination file.
  - **Example**:
    ```bash
    cp science.txt science.bak
    ```

### 6. Moving and Renaming Files
- **Command**: `mv <source_file> <destination_file>`
  - **Description**: Moves or renames the source file to the destination.
  - **Example**:
    ```bash
    mv science.bak backups/
    ```

### 7. Removing Files and Directories
- **Command**: `rm <file_name>`
  - **Description**: Removes (deletes) the specified file.
  - **Example**:
    ```bash
    rm tempfile.txt
    ```
- **Command**: `rmdir <directory_name>`
  - **Description**: Removes (deletes) an empty directory.
  - **Example**:
    ```bash
    rmdir tempstuff
    ```

### 8. Viewing File Contents
- **Command**: `cat <file_name>`
  - **Description**: Displays the entire content of the file.
  - **Example**:
    ```bash
    cat science.txt
    ```
- **Command**: `less <file_name>`
  - **Description**: Displays the content of the file one page at a time.
  - **Example**:
    ```bash
    less science.txt
    ```
- **Command**: `head <file_name>`
  - **Description**: Displays the first ten lines of the file.
  - **Example**:
    ```bash
    head science.txt
    ```
- **Command**: `tail <file_name>`
  - **Description**: Displays the last ten lines of the file.
  - **Example**:
    ```bash
    tail science.txt
    ```

### 9. Searching File Contents
- **Command**: `grep <pattern> <file_name>`
  - **Description**: Searches the file for lines that match the specified pattern.
  - **Example**:
    ```bash
    grep science science.txt
    ```
- **Command**: `grep -i <pattern> <file_name>`
  - **Description**: Searches the file for lines that match the pattern, ignoring case.
  - **Example**:
    ```bash
    grep -i science science.txt
    ```

### 10. Word and Line Count
- **Command**: `wc -w <file_name>`
  - **Description**: Counts the number of words in the file.
  - **Example**:
    ```bash
    wc -w science.txt
    ```
- **Command**: `wc -l <file_name>`
  - **Description**: Counts the number of lines in the file.
  - **Example**:
    ```bash
    wc -l science.txt
    ```

## Notes
- These commands were used to navigate, manipulate files, and explore the Unix environment during the CS2340 Unix Tutorial exercises.
- Understanding these commands is fundamental for working in Unix/Linux environments, which are common in software development and system administration.
