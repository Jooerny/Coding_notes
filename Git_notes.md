1. Open VS code terminal with Ctrl/Shift ~
# Git Cheat Sheet
## Basic Git Commands
- `git init` → Initialize a repository
- Ctrl/S file
- `git add .` → Add all changes
- `git commit -m "Message"` → Save changes
- `git push origin main` → Upload to GitHub

## How to Access & Update Notes from Anywhere
### 1. Clone your GitHub repo on a new computer
- `git clone https://github.com/YOUR_USERNAME/Coding_Notes.git`

### 2. Pull Latest Updates
If you edited your notes on GitHub and want to sync them:
- `git pull origin main`

### 3. Push New Changes
After updating your notes:
- `git add .`
- `git commit -m "Updated Python notes"`
- `git push origin main`

✅ Now your coding notes are always updated!

# How to Fix Common Issues
## How to Exit Git Commit Message Editor (Vim)
You're stuck inside Git's Vim editor after running git commit without -m. Follow these steps to exit properly.
 1. Press Esc → This exits INSERT mode
 2. Type :wq (write & quit) and press Enter
✅ This will save the commit message and exit Vim
