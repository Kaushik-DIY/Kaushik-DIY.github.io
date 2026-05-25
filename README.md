# Kaushik Mitra Venkat - Portfolio Website

Robotics Engineer specializing in perception systems, SLAM, and autonomous navigation for mobile robotics.

## 🚀 Live Website

Visit: **[kaushik.github.io](https://kaushik.github.io)** (once deployed)

## 📁 Project Structure

```
portfolio-website/
├── index.html              # Home page
├── projects.html           # All projects page
├── project-pi05.html       # Detailed Pi0.5 VLA project page
├── about.html              # About, experience, skills, certifications
├── styles.css              # Main stylesheet
├── assets/
│   ├── images/
│   │   └── photo-000.png   # Profile photo
│   └── projects/
│       ├── pi05_demo_preview.gif    # Project demo GIF
│       └── pi05_libero_10_task9.mp4 # Project demo video
└── README.md
```

## 🌐 Deploying to GitHub Pages

### Option 1: Using GitHub Web Interface (Easiest)

1. **Create a new repository** on GitHub:
   - Repository name: `<your-username>.github.io` (e.g., `Kaushik-DIY.github.io`)
   - Make it **Public**
   - Don't initialize with README

2. **Upload files**:
   - Click "uploading an existing file"
   - Drag and drop all files from the `portfolio-website` folder
   - Commit changes

3. **Enable GitHub Pages**:
   - Go to **Settings** → **Pages**
   - Source: Deploy from a branch
   - Branch: `main` / `root`
   - Click **Save**

4. **Access your site**:
   - Wait 2-3 minutes
   - Visit `https://<your-username>.github.io`

### Option 2: Using Git Command Line

```bash
# Navigate to the portfolio-website folder
cd portfolio-website

# Initialize Git repository
git init

# Add all files
git add .

# Commit
git commit -m "Initial portfolio website"

# Add remote (replace with your repository URL)
git remote add origin https://github.com/<your-username>/<your-username>.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then follow step 3 from Option 1 to enable GitHub Pages.

## 🎨 Design Features

- **Clean, professional aesthetic** optimized for German hiring managers
- **Visual-first project cards** (60% visual, 40% text)
- **Purpose-driven messaging** with "Why Robotics?" section
- **Fully responsive** - works on mobile, tablet, and desktop
- **Fast loading** - no heavy frameworks, optimized images
- **Smooth animations** - subtle scroll effects

## 📝 Customization Guide

### Update Resume

Replace `assets/Kaushik_Resume.pdf` with your latest resume.

### Add More Projects

1. Open `projects.html`
2. Copy an existing project card
3. Update:
   - Project number
   - Title and description
   - Tech stack
   - Category (`data-category`)
   - Link

### Change Colors

In `styles.css`, find and replace:
- Primary color: `#6366f1` (indigo blue)
- Background: `#F0F4F8` (light blue-gray)

### Add New Pages

1. Create new HTML file (e.g., `blog.html`)
2. Copy navigation from existing page
3. Add link to navigation in all pages

## 🛠️ Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling (no frameworks for speed)
- **Vanilla JavaScript** - Interactivity
- **GitHub Pages** - Hosting (free)

## 📧 Contact

**Kaushik Mitra Venkat**  
Robotics Engineer  
Siegen, Germany

- Email: kaushikmitra.v@gmail.com
- LinkedIn: [linkedin.com/in/kaushikmitra23](https://www.linkedin.com/in/kaushikmitra23/)
- GitHub: [github.com/Kaushik-DIY](https://github.com/Kaushik-DIY)

---

Built with purpose. © 2026 Kaushik Mitra Venkat
