## Command Line and Git Basics

### What is Command Line?
The command line, also known as the terminal or shell, is a text-based interface used to interact with the operating system by typing commands instead of using a graphical user interface (GUI).

- **Text-based interaction:** Commands are entered as text and executed by the operating system.
- **Efficiency and control:** Enables faster file management, automation, and system control.
- **Cross-platform availability:** Available on Windows (Command Prompt, PowerShell), macOS (Terminal), and Linux systems.

### Common Uses of Command Line
- Navigating the file system
- Creating, copying, moving, and deleting files or folders
- Running applications and scripts
- Installing software and managing packages
- Connecting to remote servers (SSH)
- Automating repetitive tasks

---

### Basic Command Line Commands

- **Navigation:** `pwd`, `ls`, `cd`
- **File & Directory Management:** `mkdir`, `touch`, `rm`, `cp`, `mv`
- **File Viewing:** `cat`, `less`, `head`, `tail`
- **Search & Filters:** `grep`, `find`
- **Permissions:** `chmod`, `chown`
- **System Info:** `ps`, `top`, `df`, `du`

---

## Git Basics

### What is Git?
Git is a **distributed version control system (VCS)** used to track changes in source code, collaborate with teams, and manage different versions of a project efficiently.

- **Version tracking:** Keeps a history of all code changes.
- **Collaboration:** Allows multiple developers to work on the same codebase.
- **Distributed system:** Every developer has a full copy of the repository.

### Why Use Git?
- Prevents code loss and overwrites
- Enables collaboration and parallel development
- Allows easy rollback to previous versions
- Widely used in industry with platforms like GitHub, GitLab, and Bitbucket

---

### Core Git Concepts
- **Repository:** A folder managed by Git that stores your project files and the complete history of changes.
- **Commit:** A saved snapshot of your work at a specific point in time, along with a message describing the changes.
- **Branch:** A separate line of development that lets you work on features or fixes without affecting the main code.
- **Remote:** A version of the repository stored online (such as on GitHub) used to share and sync code with others.
- **Merge:** The process of combining changes from one branch into another, usually into the main branch.

---

### Essential Git Commands (Beginner)

- **Initialize Repository:** `git init`
- **Clone Repository:** `git clone <repo-url>`
- **Check Status:** `git status`
- **Stage Changes:** `git add .`, `git add <file>`
- **Commit Changes:** `git commit -m "message"`
- **View History:** `git log`
- **Create Branch:** `git checkout -b <branch-name>`
- **Switch Branch:** `git checkout <branch-name>`
- **Merge Branch:** `git merge <branch-name>`
- **View Remotes:** `git remote -v`
- **Push Changes:** `git push origin <branch-name>`
- **Pull Updates:** `git pull`

---

### Typical Beginner Git Workflow
1. Clone or initialize a repository
2. Make code changes
3. Stage changes using `git add`
4. Commit changes using `git commit`
5. Push changes to remote repository
6. Pull updates from remote repository as needed

