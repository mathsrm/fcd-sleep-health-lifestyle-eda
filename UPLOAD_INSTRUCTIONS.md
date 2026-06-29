# GitHub upload instructions

The repository has already been created at:

```text
https://github.com/mathsrn/fcd-sleep-health-lifestyle-eda
```

## Option 1: upload using GitHub website

1. Open the repository on GitHub.
2. Click **uploading an existing file**.
3. Drag all files and folders from this project folder.
4. Write the commit message:

```text
Initial exploratory data analysis project
```

5. Click **Commit changes**.

## Option 2: upload using Git Bash or VS Code terminal

Open the terminal inside the folder `fcd-sleep-health-lifestyle-eda` and run:

```bash
git init
git add .
git commit -m "Initial exploratory data analysis project"
git branch -M main
git remote add origin https://github.com/mathsrn/fcd-sleep-health-lifestyle-eda.git
git push -u origin main
```

If Git asks for login, use your GitHub account and authenticate in the browser.
