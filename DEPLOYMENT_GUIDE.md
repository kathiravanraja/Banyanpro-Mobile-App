# Deploy BanyanPro to GitHub Pages

## Quick Setup Commands

If you prefer using Git commands, here's how to deploy:

### 1. Initialize Git Repository
```bash
cd "c:\Users\KATHIR\Downloads\Banyanpro-Mobile-App"
git init
git add .
git commit -m "Initial commit: BanyanPro mobile app"
```

### 2. Connect to GitHub Repository
```bash
# Replace 'your-username' and 'your-repo-name' with your actual values
git remote add origin https://github.com/your-username/your-repo-name.git
git branch -M main
git push -u origin main
```

### 3. Enable GitHub Pages
- Go to your repository settings
- Navigate to Pages section
- Set source to "Deploy from a branch"
- Select "main" branch
- Save settings

## File Structure
```
banyanpro-mobile-app/
├── index.html                           # Main dashboard
├── teacher_dashboard_revamped-2.html    # Teacher dashboard
├── homework_details_revamped-3.html     # Homework details
├── test-navigation.html                 # Navigation test page
└── README.md                           # Project documentation
```

## GitHub Pages URL
Your app will be live at:
`https://[your-username].github.io/[repository-name]`

## Updating Your Site
After making changes:
```bash
git add .
git commit -m "Description of changes"
git push
```

Changes will automatically deploy to GitHub Pages.
