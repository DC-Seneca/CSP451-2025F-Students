---
layout: course
title: GitHub Pages Setup Instructions
subtitle: Configuration Guide
page_header: true
page_icon: globe
---

## Manual Setup Steps

Since GitHub CLI doesn't directly support enabling GitHub Pages, please follow these manual steps:

### 1. 📂 Access Repository Settings
1. Go to the repository: https://github.com/DC-Seneca/CSP451-2025F-Students
2. Click on the **Settings** tab (top navigation bar)
3. Scroll down to **Pages** section in the left sidebar

### 2. 🔧 Configure GitHub Pages
1. Under **Source**, select **Deploy from a branch**
2. Choose **main** branch from the dropdown
3. Select **/ (root)** as the folder
4. Click **Save**

### 3. ✅ Verification
After enabling Pages:
1. GitHub will show a green checkmark and URL
2. The site will be available at: **https://dc-seneca.github.io/CSP451-2025F-Students**
3. It may take a few minutes to deploy initially

### 4. 🎯 Expected Result
Students will access a professional course website with:
- **Homepage**: Complete course overview and navigation
- **Direct Links**: Easy access to all weekly materials
- **Professional Layout**: Clean, organized presentation
- **Mobile Friendly**: Responsive design for all devices

## 📋 Files Created for GitHub Pages

- **`index.md`** - Main landing page with course navigation
- **`_config.yml`** - Jekyll configuration for GitHub Pages
- **GitHub-Pages-Setup-Instructions.md** - These setup instructions

## 🔍 Troubleshooting

**If the site doesn't load:**
1. Check that GitHub Pages is enabled in repository settings
2. Verify the main branch has the `index.md` and `_config.yml` files
3. Wait 5-10 minutes for initial deployment
4. Check the Actions tab for any build errors

**If links are broken:**
1. GitHub Pages uses Jekyll to process Markdown files
2. File paths in the navigation should work automatically
3. PDF files in References/ folder will be directly accessible

## 🚀 Benefits for Students

✅ **Easy Navigation** - Click-through access to all materials  
✅ **Professional Interface** - Clean, organized course website  
✅ **Quick Reference** - Instant access to schedules and guidelines  
✅ **Mobile Access** - Works on phones, tablets, and computers  
✅ **Always Updated** - Automatically reflects repository changes  

---

**Next Step**: Enable GitHub Pages in repository settings to activate the student course website! 🎓
