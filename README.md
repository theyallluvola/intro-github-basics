# INTRO GITHUB BASICS

## Git
Git is a powerful version control system that tracks changes to computer files and facilitates collaboration among developers. It's widely used for managing source code in software development, but it can also be used for tracking changes to any type of file, such as documents, images, or spreadsheets.

## Version Control
Version control, also known as source control, is a system that records changes to a file or set of files over time. This makes it possible to recall specific versions later.
Version control systems (VCS) are software tools that help software teams manage changes to source code over time.

## Process Of Committing A Project To Github Repository
1. Create a GitHub Repository:
- Go to your GitHub account and click the "+" icon in the top right corner.
- Select "New repository."
- Give your repository a name and add a description (optional).
- Choose whether to make it public or private.
- Do not initialize the repository with a README, .gitignore, or a license file (we'll do this locally).
- Click "Create repository."

2. Initialize Git in Your Local Project:
- Open your terminal or command prompt.
- Navigate to the directory where your project files are located using the cd command.
- Initialize a Git repository in this directory.

3. Add Files to Staging Area:
- Stage all the files in your project for the initial commit.

4. Commit Your Changes:
- Commit the changes with a descriptive message.

5. Link Your Local Repository to GitHub:
- Copy the remote repository URL from the GitHub repository page (it should look something like https://github.com/your-username/your-repository-name.git).
- Add the remote repository to your local Git repository.

6. Push Your Project to GitHub:
- Push the changes from your local repository to the remote repository on GitHub.

### Additional Tips:
- Create a README file: After pushing your project, create a README file in your local repository to provide information about your project.
- Add a .gitignore file: Create a .gitignore file to specify files or directories that you don't want to track with Git (e.g., large media files, temporary files).
- Use branches: Create branches for different features or bug fixes to work on them independently without affecting the main project.