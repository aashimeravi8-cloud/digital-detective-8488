# Mission 2: Become Comfortable with the Terminal

## 1. Task / objective

Learn how to use Terminal commands to navigate folders, create and manage files, understand command flags and pipes, and explore package managers.

## 2. Work completed

### Task 2.1 — Basic Terminal Operations

| Operation | Command | What it does |
|---|---|---|
| Current directory | `pwd` | Shows the current folder location. |
| Directory listing | `ls` | Lists files and folders. |
| Detailed listing | `ls -l` | Shows detailed file information. |
| Change directory | `cd ..` | Moves to the parent folder. |
| Create directory | `mkdir practice` | Creates a new folder. |
| Create empty file | `touch notes.txt` | Creates an empty file. |
| Copy file | `cp notes.txt copy.txt` | Creates a copy of a file. |
| Move / rename file | `mv copy.txt backup.txt` | Renames or moves a file. |
| Display file contents | `cat notes.txt` | Displays the contents of a file. |

### Task 2.2 — Practise File Changes Safely

- Created a folder named `terminal-practice`.
- Created a text file named `notes.txt`.
- Added the first line of text.
- Added a second line without removing the first line.
- Displayed both lines using the `cat` command.
- Created a backup copy of the original file.
- Renamed the backup file.

**Difference between file operations:**

- Replacing content removes the old content and adds new content.
- Appending adds new content without removing existing content.
- Copying creates another version of a file.
- Moving changes the location of a file.

### Task 2.3 — Understand Flags and Pipes

- `ls`: Displays files and folders.
- `ls -l`: Displays detailed information.
- `ls -a`: Displays hidden files also.
- `ls -h`: Displays file sizes in a human-readable format when used with a detailed listing.
- `ls -lah`: Displays hidden files, detailed information and readable file sizes.
- `ls -lah | head`: Displays only the first few lines of the listing.

**My understanding:**

- Flags change how a command works.
- A pipe (`|`) sends the output of one command as input to another command.
- The `head` command displays the first few lines of the output.

### Task 2.4 — Understand Package Managers

- Homebrew is a package manager used on macOS.
- `brew --version`: Checks the installed Homebrew version.
- `brew list`: Displays the packages managed by Homebrew.

**My understanding:**

A package manager helps us install, update and manage software. It makes software management easier and saves time.

## 3. Commands / tools used

- `pwd`: Displays the current working directory.
- `ls`: Lists files and folders.
- `cd`: Changes the current directory.
- `mkdir`: Creates a new directory.
- `touch`: Creates an empty file.
- `cp`: Copies files.
- `mv`: Moves or renames files.
- `cat`: Displays file contents.
- `echo`: Adds text to a file.
- `head`: Displays the first few lines.
- `brew`: Manages software packages on macOS.
- VS Code: Used to write and edit README files.
- Terminal: Used to execute commands.

## 4. My understanding

- Terminal allows us to interact with the computer using commands.
- Directories are used to organise files.
- Commands help us create, copy, move and manage files.
- Flags provide additional options to commands.
- Pipes connect the output of one command to another.
- Package managers make software installation and management easier.

## 5. Difficulties faced

- Initially, I was confused about some terminal commands and also pipe.