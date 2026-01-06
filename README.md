# Dr. Mukhiddin Toshpulatov - Academic Website

A modern, responsive scholarly website for Dr. Mukhiddin Toshpulatov, Senior Researcher at Voice AI Research Institute, Inha University.

## Features

- Responsive design for all devices
- Modern UI with smooth animations
- Publications filter by category
- Downloadable CV (PDF)
- Print-friendly CV page
- Mobile-friendly navigation

## Pages

- **Home** - Overview, research areas, publications preview, education, awards, skills
- **Research** - Detailed research focus areas and key contributions
- **Publications** - Journal papers, conference papers, and invited talks
- **Teaching** - Teaching experience and courses
- **CV** - Full curriculum vitae with print/download options
- **Contact** - Contact information, social profiles, CV download

## Deployment on GitHub Pages (FREE)

### Option 1: Deploy as User/Organization Site

1. Create a new repository named `muxiddin19.github.io`
2. Upload all files from this folder to the repository
3. Your site will be live at: `https://muxiddin19.github.io`

### Option 2: Deploy as Project Site

1. Create a new repository (e.g., `academic-website`)
2. Upload all files from this folder
3. Go to **Settings** > **Pages**
4. Under "Source", select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**
7. Your site will be live at: `https://muxiddin19.github.io/academic-website`

### Quick Deploy Steps

```bash
# Navigate to website folder
cd dr-muhiddin-site

# Initialize git repository
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit - Academic website"

# Add remote (replace with your repo URL)
git remote add origin https://github.com/muxiddin19/muxiddin19.github.io.git

# Push to GitHub
git push -u origin main
```

## File Structure

```
dr-muhiddin-site/
├── index.html              # Homepage
├── README.md               # This file
├── assets/
│   ├── css/
│   │   └── style.css       # Main stylesheet
│   ├── js/
│   │   └── main.js         # JavaScript functionality
│   ├── images/             # Image assets (add your photo here)
│   └── CV_Mukhiddin_Toshpulatov.pdf  # Downloadable CV
└── pages/
    ├── research.html       # Research page
    ├── publications.html   # Publications page
    ├── teaching.html       # Teaching page
    ├── cv.html             # CV page
    └── contact.html        # Contact page
```

## Customization

### Add Profile Photo

1. Add your photo to `assets/images/` (e.g., `profile.jpg`)
2. In `index.html`, replace the icon in hero section:
   ```html
   <div class="hero-image">
       <img src="assets/images/profile.jpg" alt="Dr. Mukhiddin Toshpulatov" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
   </div>
   ```

### Update Social Links

Update the URLs in `index.html` and `pages/contact.html`:
- Google Scholar profile URL
- LinkedIn profile URL
- ORCID URL
- Other academic profiles

### Update CV PDF

Replace `assets/CV_Mukhiddin_Toshpulatov.pdf` with your updated CV.

## Technologies Used

- HTML5
- CSS3 (Custom properties, Flexbox, Grid)
- Vanilla JavaScript
- Google Fonts (Inter, Playfair Display)
- Font Awesome 6 Icons

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Personal use for Dr. Mukhiddin Toshpulatov's academic website.

---

Created with care for academic excellence.
