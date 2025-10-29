# 🐍 Snake Animation Setup Guide

This guide will help you set up the contribution snake animation on your GitHub profile!

## 📋 Prerequisites

You need a GitHub repository named **exactly** like your username: `muhamedhajajii`

## 🚀 Setup Steps

### Step 1: Create Profile Repository

1. Go to GitHub and create a new repository
2. Name it: `muhamedhajajii` (must match your username exactly)
3. Make it **Public**
4. Check "Add a README file"
5. Create the repository

### Step 2: Add Files to Repository

You need to add these files to your profile repository:

1. **Copy the README.md**

    - Replace the default README.md with the new one we created

2. **Add the GitHub Actions Workflow**
    - Create folder structure: `.github/workflows/`
    - Add the file: `snake.yml` (already created in the Videos folder)

### Step 3: Enable GitHub Actions

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Click "Actions" → "General" in the left sidebar
4. Under "Workflow permissions":
    - Select "Read and write permissions"
    - Check "Allow GitHub Actions to create and approve pull requests"
    - Click "Save"

### Step 4: Run the Workflow

1. Go to "Actions" tab in your repository
2. Click "Generate Snake Animation" workflow
3. Click "Run workflow" → "Run workflow" button
4. Wait 1-2 minutes for it to complete
5. Check the "output" branch was created

### Step 5: Verify

1. Go to your profile: `https://github.com/muhamedhajajii`
2. Scroll down to see the snake animation eating your contributions! 🐍

## 🔄 Automatic Updates

The snake animation will automatically update:

-   ✅ Every 24 hours
-   ✅ Every time you push to main/master branch
-   ✅ Manually from Actions tab

## 🎨 Customization

You can customize the snake in `.github/workflows/snake.yml`:

-   Change colors
-   Change animation speed
-   Change contribution period

## 🐛 Troubleshooting

**Snake doesn't appear?**

-   Make sure the workflow ran successfully (check Actions tab)
-   Verify "output" branch exists
-   Wait a few minutes and refresh

**Workflow fails?**

-   Check workflow permissions in Settings → Actions
-   Make sure repository is public
-   Verify GitHub token has proper permissions

## 📁 File Structure

Your repository should look like:

```
muhamedhajajii/
├── .github/
│   └── workflows/
│       └── snake.yml
├── README.md
└── SNAKE_SETUP.md (optional)
```

## ✨ You're Done!

Your profile is now amazing with the contribution snake animation! 🎉

Visit: https://github.com/muhamedhajajii
