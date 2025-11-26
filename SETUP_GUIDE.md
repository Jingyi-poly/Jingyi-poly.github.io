# Personal Website Setup Guide

This is your personal academic website built with Jekyll and the Minimal Mistakes theme.

## 🎉 What's Been Created

Your website now includes the following pages:

1. **Home** (`/`) - Introduction and research interests
2. **Publications** (`/publications/`) - All your papers (published, under review, in progress)
3. **Fundings** (`/fundings/`) - Research grants and funding information
4. **Service** (`/service/`) - Teaching experience, student supervision, and academic service
5. **Experience** (`/experience/`) - Work experience, education, and skills
6. **Honors & Awards** (`/awards/`) - Academic awards and competition achievements

## 📋 Next Steps

### 1. Add Your Profile Photo

**Important**: You need to add your profile photo for the website to display correctly.

1. Prepare a square photo (recommended: 400x400 pixels or larger)
2. Save it as `bio-photo.jpg`
3. Place it in the `assets/images/` directory

### 2. Test Locally (Optional but Recommended)

Before deploying, you can test the website locally:

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# Open in browser
# Visit: http://localhost:4000
```

### 3. Deploy to GitHub Pages

Your website is ready to deploy! Follow these steps:

1. **Commit all changes**:
   ```bash
   git add .
   git commit -m "Setup personal academic website"
   ```

2. **Push to GitHub**:
   ```bash
   git push origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on "Settings"
   - Scroll down to "Pages" section
   - Under "Source", select "main" branch
   - Click "Save"

4. **Wait a few minutes** for GitHub to build your site

5. **Visit your website** at: `https://jingyi-poly.github.io`

## 🔧 Customization

### Update Personal Information

All personal information is configured in `_config.yml`. You can update:

- Name and title
- Bio and location
- Email and social links
- Site description

### Modify Pages

All page content is in the `_pages/` directory:

- `_pages/publications.md` - Update your publications
- `_pages/fundings.md` - Update funding information
- `_pages/service.md` - Update teaching and service activities
- `_pages/experience.md` - Update work experience and education
- `_pages/awards.md` - Update awards and honors

### Change Theme

You can change the color scheme by editing the `minimal_mistakes_skin` in `_config.yml`:

Options: `"default"`, `"air"`, `"aqua"`, `"contrast"`, `"dark"`, `"dirt"`, `"neon"`, `"mint"`, `"plum"`, `"sunrise"`

## 📁 File Structure

```
.
├── _config.yml              # Main configuration file
├── _data/
│   └── navigation.yml       # Navigation menu
├── _pages/                  # All website pages
│   ├── publications.md
│   ├── fundings.md
│   ├── service.md
│   ├── experience.md
│   └── awards.md
├── assets/
│   └── images/              # Images directory
│       └── bio-photo.jpg    # Your profile photo (ADD THIS!)
├── index.html               # Home page
└── SETUP_GUIDE.md          # This file
```

## 🎨 Design Reference

This website is designed based on the style of: https://yining043.github.io/service/

## 📝 Updating Content

### Adding a New Publication

Edit `_pages/publications.md` and add your publication in the appropriate section:

```markdown
1. **Your Name**, Co-author. "Paper Title". *Journal Name*, Year.
```

### Adding a New Award

Edit `_pages/awards.md` and add your award:

```markdown
### Year
**Award Name**  
*Organization/Conference*

- Description of the award
```

### Updating Research Interests

Edit `index.html` to update your research interests and bio.

## 🆘 Troubleshooting

### Website not showing up?

1. Make sure GitHub Pages is enabled in repository settings
2. Check that you pushed to the `main` branch
3. Wait 5-10 minutes for GitHub to build the site

### Profile photo not showing?

1. Make sure the file is named exactly `bio-photo.jpg`
2. Make sure it's in the `assets/images/` directory
3. Try clearing your browser cache

### Navigation links not working?

1. Make sure all files in `_pages/` have the correct `permalink` in the front matter
2. Check that `_data/navigation.yml` has the correct URLs

## 📚 Resources

- [Minimal Mistakes Documentation](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

## ✅ Checklist

- [ ] Add profile photo (`assets/images/bio-photo.jpg`)
- [ ] Review and update all pages content
- [ ] Test locally (optional)
- [ ] Commit and push to GitHub
- [ ] Enable GitHub Pages
- [ ] Visit your live website!

---

**Your website URL**: https://jingyi-poly.github.io

Good luck with your new academic website! 🚀

