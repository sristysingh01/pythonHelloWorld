# Python Hello World

A beginner-friendly Python script that prints a greeting to the terminal.

## What it does

Running the script prints:
```
Hello, World!
Hello, sristy singh
```

## How to run

1. Open Terminal
2. Navigate to this folder:
   ```bash
   cd ~/Downloads/pythonHelloWorld
   ```
3. Run the script:
   ```bash
   python3 hello_world.py
   ```

---

## Git & GitHub Setup Guide

### Step 1 — Create a GitHub Account (do this in your browser)

1. Go to [https://github.com](https://github.com)
2. Click **Sign up**
3. Enter your email, create a password, and choose a username
4. Verify your email address

### Step 2 — Initialize Git on your computer (Terminal commands)

Open Terminal and run these commands one by one:

```bash
cd ~/Downloads/pythonHelloWorld
git init
git add hello_world.py README.md
git commit -m "Initial commit: Hello World script with setup guide"
```

### Step 3 — Create a new repository on GitHub (do this in your browser)

1. Log in to [github.com](https://github.com)
2. Click the **+** icon in the top-right corner → **New repository**
3. Name it `pythonHelloWorld`
4. Leave it set to **Public**
5. Do **NOT** check "Add a README" (you already have files)
6. Click **Create repository**
7. Copy the repository URL shown on the next page — it looks like:
   `https://github.com/YOUR_USERNAME/pythonHelloWorld.git`

### Step 4 — Connect your local project to GitHub and push (Terminal commands)

Replace `YOUR_USERNAME` with your actual GitHub username:

```bash
git remote add origin https://github.com/YOUR_USERNAME/pythonHelloWorld.git
git branch -M main
git push -u origin main
```

### Done!

Refresh your GitHub repository page in the browser — you should see both files (`hello_world.py` and `README.md`) listed there.
