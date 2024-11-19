# Unix Tutorial Instructions

### Introduction to the Unix Operating System
This project introduces you to the Unix operating system, which is essential for many projects throughout this course and future courses. The tasks will be performed on the Lyle Genuse servers, so ensure that you have created a Genuse account if you haven't already.

### Account Setup
1. **Create a Genuse Account**: If you don't have a Lyle Genuse account from a previous course, set up a new account as instructed on the [CS 2340 Tools website](https://s2.smu.edu/~manikas/Courses/CS2340_Tools/CS2340_Tools.html).
2. **Set Up Console Window**: Use the instructions provided on the Tools website to configure a Console Window on your PC to access your Genuse account via SSH.
3. **File Transfer Program**: Set up a program on your PC to transfer files between your Lyle Genuse account and your PC.

### UNIX Tutorial for Beginners
Using the console window, complete the following sections from the "UNIX Tutorial for Beginners":

#### **Tutorial One**
1. **Listing Files and Directories**:
   - Use the `ls` command to list the files and directories in your home directory.
   - To list hidden files (those starting with a dot), use `ls -a`.

2. **Making Directories**:
   - Create a subdirectory named `unixstuff` using `mkdir unixstuff`.
   - Verify by typing `ls`.

3. **Changing to a Different Directory**:
   - Change to the `unixstuff` directory using `cd unixstuff`.
   - Type `ls` to verify that it is empty.

4. **Special Directories (. and ..)**:
   - Use `ls -a` to view the `.` (current directory) and `..` (parent directory).
   - Type `cd .` to stay in the current directory and `cd ..` to go back to your home directory.

5. **Pathnames and Navigation**:
   - Use `pwd` (print working directory) to view the full pathname of your current directory.
   - Explore the filesystem using `cd`, `ls`, and `pwd`.

6. **Creating and Navigating Subdirectories**:
   - Create a directory named `backups` inside the `unixstuff` directory using `mkdir unixstuff/backups`.

#### **Tutorial Two**
1. **Getting Files onto the Server**:
   - Download the file `science.txt` and transfer it to your home directory on the server.
   - Use `ls` to verify the presence of `science.txt`.

2. **Copying Files**:
   - Use `cp science.txt science.bak` to create a backup of `science.txt`.

3. **Moving Files**:
   - Move `science.bak` to the `backups` directory using `mv science.bak backups/`.

4. **Removing Files and Directories**:
   - Create a copy of `science.txt` named `tempfile.txt` and remove it using `rm tempfile.txt`.
   - Create and remove a directory named `tempstuff` using `mkdir tempstuff` and `rmdir tempstuff`.

5. **Viewing File Contents**:
   - Use `cat science.txt` to display the entire file content.
   - Use `less science.txt` to view the file one page at a time, pressing space to scroll.
   - Use `head` and `tail` to display the first or last lines of `science.txt`.

6. **Searching File Contents**:
   - Use `grep science science.txt` to search for the word "science" in the file.
   - Use the `-i` option for case-insensitive search (`grep -i science science.txt`).

7. **Word Count**:
   - Use `wc -w science.txt` to count the words in the file.
   - Use `wc -l science.txt` to count the lines.

### Exercises
- **Exercise 1a**: Create another directory inside `unixstuff` named `backups`.
- **Exercise 1b**: Use `cd`, `ls`, and `pwd` commands to explore the filesystem.
- **Exercise 2a**: Create a backup of `science.txt` by copying it to a file named `science.bak`.
- **Exercise 2b**: Create a directory called `tempstuff` and remove it using the `rmdir` command.

### Summary of Commands Used
| Command | Description |
|---------|-------------|
| `ls` | List files and directories |
| `ls -a` | List all files, including hidden files |
| `mkdir` | Create a directory |
| `cd` | Change to a named directory |
| `pwd` | Display the path of the current directory |
| `cp` | Copy a file |
| `mv` | Move or rename a file |
| `rm` | Remove a file |
| `rmdir` | Remove a directory |
| `cat` | Display file content |
| `less` | View file content one page at a time |
| `head` | Display the first few lines of a file |
| `tail` | Display the last few lines of a file |
| `grep` | Search a file for keywords |
| `wc` | Count the number of lines/words/characters in a file |

### Notes
- This project helps familiarize with Unix/Linux systems, a crucial skill in software engineering, system administration, and DevOps.
- The hands-on exercises covered foundational Unix commands for navigating and managing files within a Linux environment.
