# Sarawut Ounjai - Academic Portfolio Website

Personal academic portfolio website built with HTML & CSS.

## 🌐 Live Demo

Visit: **https://ounjais.github.io**

## 📁 File Structure

```
├── index.html          # About page (homepage)
├── publications.html   # Publications list
├── cv.html            # Curriculum Vitae
├── achievements.html  # Awards & Certifications
├── contact.html       # Contact information
├── assets/
│   └── css/
│       └── style.css  # Main stylesheet
├── images/            # Profile images (create this folder)
│   └── profile.jpg    # Your profile photo
└── files/             # Downloadable files (create this folder)
    └── CV_Sarawut_Ounjai.pdf
```

## 🚀 Deploy to GitHub Pages

### Step 1: Create Repository
Create a new repository named `ounjais.github.io` (use your GitHub username)

### Step 2: Upload Files
Upload all files maintaining the folder structure above.

### Step 3: Enable GitHub Pages
1. Go to repository **Settings** → **Pages**
2. Under "Source", select **main** branch
3. Click **Save**

### Step 4: Access Your Site
Your website will be live at: `https://ounjais.github.io`

## 🖼️ Adding Profile Photo

1. Create an `images` folder in your repository
2. Upload your photo as `images/profile.jpg`
3. In each HTML file, find:
   ```html
   <div class="profile-image-placeholder">SO</div>
   ```
4. Replace with:
   ```html
   <img src="images/profile.jpg" alt="Sarawut Ounjai" class="profile-image">
   ```

## ✏️ Customization

### Update Content
Each page is a separate HTML file - edit directly to update content.

### Change Colors
Edit `assets/css/style.css` and modify the CSS variables at the top:
```css
:root {
    --color-primary: #1a365d;    /* Main dark blue */
    --color-secondary: #2c5282;  /* Secondary blue */
    --color-accent: #ed8936;     /* Orange accent */
}
```

## 📱 Features

- ✅ Responsive design (mobile-friendly)
- ✅ Clean academic layout
- ✅ Separate pages for easy navigation
- ✅ Social links (Google Scholar, ORCID, GitHub, LinkedIn)
- ✅ Mobile navigation menu
- ✅ No JavaScript dependencies for basic functionality

## 📄 License

Feel free to use and modify for your own academic portfolio.
