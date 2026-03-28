# Git Automater

An automated contribution generator that runs daily to keep your GitHub activity graph active.

## Setup Instructions

Even with the correct workflow file, there are two manual steps you must perform in your GitHub repository settings for the automation to work correctly:

1. **Enable Workflow Permissions:**
   - Go to your repo **Settings > Actions > General**.
   - Scroll down to "Workflow permissions" and select **"Read and write permissions"**.
   - Check the box **"Allow GitHub Actions to create and approve pull requests"**.
   - Click "Save".

2. **Show Private Contributions (If applicable):**
   - If this repository is Private, go to your GitHub **Profile Settings > Contributions**.
   - Check the box that says **"Show private contributions on my profile"**.
   - If you don't do this, the green dots will be invisible to everyone else!
