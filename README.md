# 1. Initialize a new Git repository
git init -b main

# 2. Add all your files to be tracked
git add .

# 3. Save your files with a commit message
git commit -m "Initial commit: Add logistic regression project for social network ads"

# 4. Go to GitHub.com, create a new *empty* repository (do NOT add a README or .gitignore)
#    After creating it, copy its URL.

# 5. Link your local folder to the GitHub repository
#    (Replace with your repository's URL)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git

# 6. Push your files to GitHub
git push -u origin main
