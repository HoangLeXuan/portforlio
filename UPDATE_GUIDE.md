# 📝 Portfolio Update Guide

This guide will help you easily update your portfolio with your personal information. Your portfolio now has a **beautiful sidebar layout** inspired by GitHub!

## 🔍 What to Look For

In the HTML file (`index.html`), look for text inside square brackets like `[YOUR NAME]`. These are placeholders you need to replace with your actual information.

## 📋 Step-by-Step Update Checklist

### 1. Profile Section (Sidebar)
Find and replace these in the sidebar:
- `[YOUR FULL NAME]` → Your actual name (e.g., "John Smith")
- `[YOUR PROFESSIONAL TITLE]` → Your job title (e.g., "Full Stack Developer")  
- `[YOUR BRIEF BIO]` → 2-3 sentences about yourself and what you do

### 2. Projects Section
For each project, replace:
- `[PROJECT 1 TITLE]` → Your project name (e.g., "AI Chatbot App")
- `[PROJECT 1 DESCRIPTION]` → Detailed project description
- `[GITHUB_REPO_URL]` → Link to your GitHub repository
- `[LIVE_DEMO_URL]` → Link to live demo (if available)
- `[Tech1]`, `[Tech2]`, `[Tech3]` → Technologies used (e.g., "React", "Node.js", "MongoDB")

**To add more projects:**
1. Copy the entire `project-card` div block
2. Paste it after the last project
3. Update the placeholder text

### 3. Skills Section
Replace:
- `[Language1]`, `[Language2]`, etc. → Programming languages (e.g., "JavaScript", "Python")
- `[Framework1]`, `[Framework2]`, etc. → Frameworks you use (e.g., "React", "Express")
- `[Tool1]`, `[Tool2]`, etc. → Tools and technologies (e.g., "Git", "Docker")

### 4. Experience Section
For each job, replace:
- `[JOB TITLE]` → Your position (e.g., "Software Engineer")
- `[COMPANY NAME]` → Company name
- `[START DATE] - [END DATE]` → Employment dates (e.g., "Jan 2022 - Present")
- `[Key achievement or responsibility 1]` → Your accomplishments

**To add more experience:**
1. Copy the entire `timeline-item` div
2. Paste it where you want it chronologically
3. Update the information

### 5. Education Section
Replace:
- `[DEGREE NAME]` → Your degree (e.g., "Bachelor of Computer Science")
- `[UNIVERSITY NAME]` → School name
- `[GRADUATION YEAR]` → Year you graduated
- `[Any relevant details...]` → GPA, honors, relevant coursework

### 6. Contact Information (Sidebar)
Replace in the sidebar contact section:
- `[YOUR_EMAIL]` → Your email address
- `[YOUR_GITHUB]` → Your GitHub username  
- `[YOUR_LINKEDIN]` → Your LinkedIn profile name
- `[YOUR_LOCATION]` → Your city/location (e.g., "San Francisco, CA")

### 7. Tech Stack (Sidebar)
Replace the tech tags in the sidebar:
- `[Language1]`, `[Language2]` → Programming languages (e.g., "JavaScript", "Python")
- `[Framework1]`, `[Framework2]` → Frameworks (e.g., "React", "Node.js")
- `[Tool1]`, `[Tool2]` → Tools (e.g., "Git", "Docker")

### 8. Experience (Sidebar)
For each job in the sidebar:
- `[START] - [END]` → Date range (e.g., "2022 - Present")
- `[JOB TITLE]` → Your position (e.g., "Software Engineer")
- `[COMPANY NAME]` → Company name

### 9. Main Content Area
Replace in the main content:
- `[NUMBER]` in "Showcasing [NUMBER] projects" → Actual number of projects
- `[DETAILED DESCRIPTION ABOUT YOURSELF]` → Longer description in the About section
- `[Current project or learning goal 1]` → What you're currently working on

### 10. Other Updates
- `[YOUR NAME]` in the footer → Your name for copyright
- `[Main Language]` → The primary programming language for each project

## 🖼️ Project Icons

Your projects now use **emoji icons** for a clean, modern look:
- 🔗 for web/link projects
- 📱 for mobile apps  
- 🤖 for AI/ML projects
- 🎮 for games
- 📊 for data projects

**To change project icons:**
1. Find `<div class="project-icon">🔗</div>` in your project
2. Replace the emoji with your preferred icon

**Popular project emojis:** 💻 🌐 ⚡ 🚀 🎯 📈 🔧 🎨 📱 🖥️

## 📄 Adding Your Resume - Two Ways to View!

Your portfolio now has **TWO resume buttons** for better user experience:

1. **📄 View Resume** - Opens your resume in a new browser tab (users can view it online)
2. **⬇️ Download** - Downloads the resume file to user's computer

### How to Add Your Resume:
1. Save your resume as `resume.pdf` in the same folder as your HTML file
2. Both buttons will automatically work!

### Pro Tips:
- **PDF format is best** - works on all devices and browsers
- **Keep file size under 5MB** for faster loading
- **Name it exactly `resume.pdf`** or update the file path in HTML
- The "View Resume" button is great for quick viewing without downloading

## 🎨 Theme Colors (Optional)

If you want to change the blue accent color:
1. Open `styles.css`
2. Find `--accent-color: #2563eb;`
3. Replace with your preferred color code

## 📱 Testing Your Changes

1. Open `index.html` in your web browser
2. Check that all information displays correctly
3. Test the theme toggle button (moon/sun icon)
4. Try the navigation links
5. Test the resume download button

## 🚀 Publishing to GitHub Pages

1. Create a new repository on GitHub
2. Upload all your files (`index.html`, `styles.css`, `script.js`, `resume.pdf`)
3. Go to repository Settings → Pages
4. Select "Deploy from a branch" → "main"
5. Your portfolio will be live at `https://yourusername.github.io/repository-name`

## ✅ Quick Checklist

- [ ] Updated personal information
- [ ] Added project descriptions and links
- [ ] Listed skills and technologies
- [ ] Added work experience
- [ ] Added education details
- [ ] Updated contact information
- [ ] Added resume file
- [ ] Tested in browser
- [ ] Published to GitHub Pages

## 🆘 Need Help?

- All placeholder text is in `[square brackets]` - just search for `[` to find them all
- The emoji placeholders (🖼️, 🤖) can be replaced with real images
- Each section is clearly commented in the HTML file
- The CSS uses simple variables, so colors are easy to change

**Pro Tip:** Use your browser's "Find" function (Ctrl+F or Cmd+F) to search for `[` to quickly locate all placeholders! 