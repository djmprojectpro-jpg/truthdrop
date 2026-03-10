# Initialize git (if needed)
git init

# Configure git (if needed)
git config --global user.name "Your Name"
git config --global user.email "your.email@github.com"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/your-repo.git

# Stage and commit all changes
git add .
git commit -m "Your commit message"

# Push to GitHub
git push -u origin main
