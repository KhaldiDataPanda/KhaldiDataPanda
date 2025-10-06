# GitHub Actions Workflows

## Deploy Profile to GitHub Pages

This workflow automatically converts your profile README.md to a beautiful HTML page and deploys it to GitHub Pages.

### Features:
- ✅ Automatic deployment on push to main branch
- ✅ Daily updates at midnight UTC to refresh GitHub stats
- ✅ Manual trigger option via workflow_dispatch
- ✅ Beautiful Dracula-themed design
- ✅ Responsive layout for mobile and desktop
- ✅ Auto-updates timestamp

### Setup Instructions:

1. **Enable GitHub Pages:**
   - Go to your repository settings
   - Navigate to "Pages" in the left sidebar
   - Under "Build and deployment", select:
     - Source: **GitHub Actions**

2. **Commit and Push:**
   - Commit the workflow file to your repository
   - Push to the main branch
   - The workflow will automatically run

3. **Access Your Page:**
   - After successful deployment, your page will be available at:
     - `https://khaldidatapanda.github.io/KhaldiDataPanda/`

### Workflow Triggers:
- **Push to main:** Runs automatically when you update your README
- **Daily schedule:** Runs at 00:00 UTC to update GitHub stats
- **Manual trigger:** Run from the Actions tab when needed

### Customization:
You can customize the HTML styling by modifying the CSS in the `convert.js` section of the workflow file.

### Troubleshooting:
- If deployment fails, check the Actions tab for error messages
- Ensure GitHub Pages is enabled with "GitHub Actions" as the source
- Verify repository permissions include "Read and write permissions" for workflows
