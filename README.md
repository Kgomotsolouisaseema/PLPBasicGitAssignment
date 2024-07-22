## GitHub Workflow Assignment

The objective of this assignment is to familiarize students with the basic workflow of creating a GitHub repository, connecting it to a local folder, and making commits and pushes.

### Requirements:
- A GitHub account (create one if you don't have it already).
- Git installed on your local machine.
- A code editor of your choice (e.g., Visual Studio Code, Sublime Text).

### Steps:

#### Task 1: Repository Setup

**1. GitHub Repository Creation:**
  1.1. Log in to your GitHub account.
  1.2. Create a new repository on GitHub (let's call it "PLPBasicGitAssignment").
  1.3. Initialize it with a README file.

#### Task 2: Local Setup

**2. Local Folder Setup:**
  2.1. Create a new folder on your local machine (e.g., "PLPBasicGitAssignment").
  2.2. Open a terminal or command prompt and navigate to the created folder.

**3. Git Initialization:**
  3.1. Initialize a new Git repository in your local folder.
     ```bash
     git init
     ```

**4. Connecting to GitHub:**
  4.1. Link your local repository to the GitHub repository you created in Task 1.
     ```bash
     git remote add origin <repository-url>
     ```
     Replace `<repository-url>` with the actual URL of your GitHub repository.

#### Task 3: Making Changes

**5. Create a File:**
  5.1. Inside your local folder, create a new text file (e.g., `hello.txt`).
  5.2. Add a simple text message (e.g., "Hello, Git!").

**6. Committing Changes:**
  6.1. Stage the changes.
     ```bash
     git add hello.txt
     ```
  6.2. Commit the changes.
     ```bash
     git commit -m "Add hello.txt with a greeting"
     ```

#### Task 4: Pushing to GitHub

**7. Pushing to GitHub:**
  7.1. Push the committed changes to your GitHub repository.
     ```bash
     git push -u origin main
     ```

#### Task 5: Verification

**8. Verify on GitHub:**
  8.1. Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.

### Submission:
- Ensure all changes are pushed to your GitHub repository.
- Share the link to your GitHub repository with the instructor or submit it as per the class instructions.

