<h1>A showcase of a to-do list using Python</h1>

<h2>How to use this example</h2>

<h3>Step 1: Install Git (if not already installed)</h3>

If Git isn't installed on your system, download and install it from the website below:
- https://git-scm.com/downloads

To check if Git is installed, run:

``` git --version ```

<h3>Step 2: Create a GitHub Repository</h3>

- Go to GitHub and log into your account
- Click on "New" to create a repository
- Set the repository name as ```simple-todo-list```
- Choose visibility (public or private)
- Check "Add a README file" if desired
- Click "Create repository"

<h3>Step 3: Set Up Your Local Project</h3>

Create a folder on your computer for the project:

```mkdir simple-todo-list```

```cd simple-todo-list```

Create the Python script (```todo_list.py```):

```nano todo_list.py```

Paste your to-do list Python code, then save and exit (```CTRL + X```, then ```Y```, then ```Enter```).

<h3>Step 4: Initialize Git and Link to GitHub</h3>

Run the following commands in your project folder:

- Initialize Git in the directory:

```git init```

- Link your local repo to GitHub (replace <your-username> with your GitHub username):

```git remote add origin https://github.com/<your-username>/simple-todo-list.git```

<h3>Step 5: Add and Commit Files</h3>

- Add all files to the staging area:

```git add .```

- Commit the files with a message:

```git commit -m "Initial commit - Simple To-Do List app"```

<h3>Step 6: Push to GitHub</h3>

Upload your local project to GitHub with:

```git branch -M main```
```git push -u origin main```

<h3>Step 7: Verify on GitHub</h3>

- Go to your GitHub repository (https://github.com/<your-username>/simple-todo-list) and check if the files are uploaded.

<h3>Step 7: Add a README.md File</h3>

Create a ```README.md``` to explain your project:

```echo "# Simple To-Do List in Python" > README.md```

```git add README.md```

```git commit -m "Added README"```

```git push```

And that is how you create a simple to-do list using Python and upload it to GitHub. Below is a sample of what coule be on the ```README.md```

<h1></h1>

Example of content cotained in the ```README.md```

# Simple To-Do List in Python

A beginner-friendly command-line to-do list app to add, view, and remove tasks.

## Features
- Add tasks to your list
- View all tasks
- Remove completed tasks

## Usage
Run the script with:

```python todo_list.py```


Enjoy organizing your tasks!
