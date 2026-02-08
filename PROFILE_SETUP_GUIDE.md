# 🚀 Complete GitHub Profile Setup Guide

## 📋 Table of Contents
1. [Prerequisites](#prerequisites)
2. [Repository Setup](#repository-setup)
3. [WakaTime Integration](#wakatime-integration)
4. [LeetCode Integration](#leetcode-integration)
5. [Snake Animation Setup](#snake-animation-setup)
6. [GitHub Skyline](#github-skyline)
7. [Verification Checklist](#verification-checklist)
8. [Troubleshooting](#troubleshooting)

---

## 🔧 Prerequisites

Before starting, ensure you have:
- [ ] A GitHub account (username: `Ady-OZz`)
- [ ] Git installed on your computer
- [ ] VS Code or any text editor
- [ ] A resume PDF file ready

---

## 📁 Repository Setup

### Step 1: Create Profile Repository

1. Go to GitHub.com and click **New Repository**
2. Name it **exactly** as your username: `Ady-OZz`
3. Make it **Public**
4. Check **"Add a README file"**
5. Click **Create Repository**

### Step 2: Upload Files

```bash
# Clone the repository
git clone https://github.com/Ady-OZz/Ady-OZz.git
cd Ady-OZz

# Copy the optimized README
# (Replace with the content from README_OPTIMIZED.md)

# Add your resume
# Place your resume.pdf file in the root directory

# Commit and push
git add .
git commit -m "Initial profile setup"
git push origin main
```

### Step 3: Create GitHub Actions Workflow

1. Create directory structure:
```bash
mkdir -p .github/workflows
```

2. Create file `.github/workflows/snake.yml`
3. Copy the content from the `snake.yml` file provided

4. Commit and push:
```bash
git add .github/workflows/snake.yml
git commit -m "Add snake animation workflow"
git push origin main
```

---

## ⏱️ WakaTime Integration

### What is WakaTime?
WakaTime tracks your coding time automatically and displays it on your profile.

### Setup Steps:

#### 1. Create WakaTime Account
- Go to [wakatime.com](https://wakatime.com)
- Sign up with GitHub
- Verify your email

#### 2. Install WakaTime Plugin

**For VS Code:**
1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X)
3. Search for "WakaTime"
4. Click Install
5. Enter your API key when prompted (find it at wakatime.com/settings/account)

**For Other IDEs:**
- Visit [wakatime.com/plugins](https://wakatime.com/plugins)
- Download plugin for your IDE

#### 3. Find Your WakaTime Username
1. Go to [wakatime.com/settings/account](https://wakatime.com/settings/account)
2. Your username is displayed at the top
3. Current username: `AdyOZz`

#### 4. Verify It's Working
- The WakaTime stats widget in your README will show data after ~24 hours of coding
- Check your dashboard at wakatime.com/dashboard

### Current Integration:
```markdown
![WakaTime Stats](https://github-readme-stats.vercel.app/api/wakatime?username=AdyOZz&theme=gruvbox&layout=compact&hide_border=true)
```

---

## 🧠 LeetCode Integration

### Setup Steps:

#### 1. Find Your LeetCode Username
1. Go to [leetcode.com](https://leetcode.com)
2. Log in to your account
3. Click on your profile picture (top right)
4. Your username appears in the URL: `leetcode.com/u/YOUR_USERNAME/`
5. Current username: `adityasridharofficial`

#### 2. Make Profile Public
1. Go to LeetCode Settings
2. Ensure your profile is **Public**
3. Save changes

#### 3. Verify Stats Display
- Stats will appear immediately once profile is public
- The widget automatically updates with your latest submissions

### Current Integration:
```markdown
![LeetCode Stats](https://leetcard.jacoblin.cool/adityasridharofficial?theme=dark&font=Baloo&ext=activity)
```

### Available Themes:
- `dark` (current)
- `light`
- `wtf`
- `unicorn`
- `nord`
- `forest`

To change theme, replace `dark` in the URL.

---

## 🐍 Snake Animation Setup

### How It Works:
The snake "eats" your GitHub contributions to create an animated graphic.

### Setup Steps:

#### 1. Enable GitHub Actions
1. Go to your repository: `github.com/Ady-OZz/Ady-OZz`
2. Click **Settings** tab
3. Click **Actions** → **General** (left sidebar)
4. Under "Actions permissions", select **Allow all actions and reusable workflows**
5. Click **Save**

#### 2. Set Workflow Permissions
1. In the same Settings → Actions → General page
2. Scroll to **Workflow permissions**
3. Select **Read and write permissions**
4. Check **Allow GitHub Actions to create and approve pull requests**
5. Click **Save**

#### 3. Run the Workflow
1. Go to **Actions** tab in your repository
2. Click **Generate Snake** workflow (left sidebar)
3. Click **Run workflow** button (right side)
4. Select branch: `main`
5. Click green **Run workflow** button
6. Wait 30-60 seconds for completion

#### 4. Verify Output Branch
1. Go to your repository main page
2. Click branch dropdown (says "main")
3. You should see a new branch called `output`
4. This branch contains the generated snake SVG

### Troubleshooting Snake Animation:

**Problem: Workflow fails**
- ✅ Check that Actions are enabled
- ✅ Verify write permissions are granted
- ✅ Ensure `GITHUB_TOKEN` has proper permissions

**Problem: Snake not visible on profile**
- ✅ Wait 5-10 minutes after first workflow run
- ✅ Hard refresh your profile page (Ctrl+Shift+R)
- ✅ Check that `output` branch exists
- ✅ Verify the SVG file exists at: `github.com/Ady-OZz/Ady-OZz/blob/output/github-contribution-grid-snake.svg`

**Problem: Snake is blank**
- ✅ Make sure you have GitHub contributions (green squares on your profile)
- ✅ Make contributions by committing code to any repository

---

## 🏙️ GitHub Skyline

### What is Skyline?
A 3D representation of your GitHub contributions as a city.

### Setup Steps:

#### 1. Generate Your Skyline
1. Visit: `https://skyline.github.com/Ady-OZz/2024`
2. Wait for the 3D model to load
3. It will show your 2024 contributions

#### 2. Download Image (Optional)
1. Take a screenshot of the 3D model
2. Or use the direct PNG URL in README

#### 3. Change Year
- For 2025: `https://skyline.github.com/Ady-OZz/2025`
- For 2023: `https://skyline.github.com/Ady-OZz/2023`

### Current Integration:
```markdown
[![2024 Skyline](https://skyline.github.com/Ady-OZz/2024.png)](https://skyline.github.com/Ady-OZz/2024)
```

---

## ✅ Verification Checklist

Use this checklist to verify everything is working:

### Profile Repository
- [ ] Repository named `Ady-OZz` exists
- [ ] Repository is **Public**
- [ ] README.md is present and displays on profile

### README Content
- [ ] Animated header loads
- [ ] Social icons are clickable
- [ ] About Me section displays correctly
- [ ] Tech stack icons visible

### GitHub Stats
- [ ] Overall stats card loads
- [ ] Top languages card loads
- [ ] Contribution streak loads
- [ ] Activity graph displays
- [ ] Profile summary cards visible
- [ ] GitHub trophies display

### Integrations
- [ ] WakaTime stats appear (after 24hrs of coding)
- [ ] LeetCode stats card loads
- [ ] Snake animation visible
- [ ] Skyline image loads
- [ ] Resume link works (after uploading resume.pdf)

### GitHub Actions
- [ ] Actions are enabled
- [ ] Snake workflow runs without errors
- [ ] `output` branch exists
- [ ] Snake SVG file exists in output branch
- [ ] Workflow runs on schedule (every 12 hours)

### Visual Elements
- [ ] Profile view counter updates
- [ ] All images load without broken links
- [ ] Theme colors are consistent
- [ ] Mobile responsive (check on phone)

---

## 🔧 Troubleshooting

### Common Issues and Solutions

#### 1. Widgets Not Loading

**Problem:** Stats cards show "Error: Request failed"

**Solutions:**
- Wait 5-10 minutes and refresh
- Check your internet connection
- Verify username is spelled correctly
- Try clearing browser cache

---

#### 2. WakaTime Stats Empty

**Problem:** WakaTime widget shows no data

**Solutions:**
- Ensure WakaTime plugin is installed in your IDE
- Verify API key is entered correctly
- Code for at least 1 hour to see data
- Wait 24 hours for first sync
- Check wakatime.com/dashboard to verify tracking

---

#### 3. LeetCode Stats Not Showing

**Problem:** LeetCode card doesn't load

**Solutions:**
- Verify profile is public on LeetCode
- Check username spelling: `adityasridharofficial`
- Try different theme in URL
- Clear browser cache

---

#### 4. Snake Animation Missing

**Problem:** Snake doesn't appear on profile

**Solutions:**
```bash
# Check if output branch exists
git fetch origin
git branch -a | grep output

# If output branch missing, re-run workflow:
# 1. Go to Actions tab
# 2. Click "Generate Snake"
# 3. Click "Run workflow"

# Verify file exists
# Visit: github.com/Ady-OZz/Ady-OZz/blob/output/github-contribution-grid-snake.svg
```

---

#### 5. GitHub Actions Failing

**Problem:** Workflow shows red X (failed)

**Solutions:**
1. Check error message in Actions log
2. Common fixes:
   - Enable Actions in Settings
   - Grant write permissions
   - Verify snake.yml syntax
   - Re-run the workflow

---

#### 6. Resume Link Broken

**Problem:** Resume link returns 404

**Solutions:**
```bash
# Ensure resume.pdf is in root directory
ls -la resume.pdf

# If missing, add it:
# 1. Place resume.pdf in repository root
# 2. Commit and push
git add resume.pdf
git commit -m "Add resume"
git push origin main
```

---

#### 7. Profile Not Updating

**Problem:** Changes to README don't show on profile

**Solutions:**
- Wait 2-5 minutes for GitHub to process
- Hard refresh: Ctrl+Shift+R (Windows/Linux) or Cmd+Shift+R (Mac)
- Clear browser cache
- Try incognito/private browsing mode
- Check if you're viewing the correct profile

---

## 🎯 Best Practices

### Keeping Profile Fresh

1. **Regular Commits:** Contribute to repositories regularly to keep the activity graph active

2. **Update Stats Annually:**
   - Update Skyline year in README each January
   - Review and update "Currently Learning" section

3. **Maintain Resume:**
   - Update resume.pdf every 3-6 months
   - Ensure it matches your latest skills

4. **Monitor Integrations:**
   - Check WakaTime weekly to ensure it's tracking
   - Solve LeetCode problems regularly for stats

5. **GitHub Actions:**
   - Snake animation auto-updates every 12 hours
   - Check Actions tab monthly for failed runs

---

## 📊 Statistics Explained

### GitHub Stats Card
- **Total Stars:** Stars received on your repositories
- **Total Commits:** All commits across all repos
- **PRs:** Pull requests you've made
- **Issues:** Issues you've contributed to
- **Contributed to:** Number of repos you've contributed to

### Top Languages
- Based on repository code composition
- Updates automatically
- Doesn't count forked repos by default

### Contribution Streak
- Consecutive days with contributions
- Any commit, PR, or issue counts
- Resets at midnight UTC

---

## 🚀 Next Steps

### Optional Enhancements

1. **Spotify Integration:**
   - Show currently playing song
   - Visit: github.com/kittinan/spotify-github-profile

2. **Blog Posts:**
   - Auto-sync latest blog posts
   - Use: github.com/gautamkrishnar/blog-post-workflow

3. **Visitor Map:**
   - Show visitor locations
   - Use: github.com/techinpark/visitor-badge

4. **Custom Widgets:**
   - Create your own stats
   - Use GitHub APIs

---

## 📞 Support

If you encounter issues not covered here:

1. Check GitHub Actions logs for error details
2. Search GitHub Issues for the specific widget/tool
3. Verify all URLs and usernames are correct
4. Wait 24 hours for third-party APIs to sync

---

## 🎉 Congratulations!

Your GitHub profile is now complete with:
- ✅ Professional branding
- ✅ Live activity tracking
- ✅ Coding statistics
- ✅ Problem-solving proof
- ✅ Automated updates

**Profile URL:** https://github.com/Ady-OZz

Share your profile with recruiters and on LinkedIn!

---

<p align="center">
  Made with ❤️ for Aditya Sridhar
</p>
