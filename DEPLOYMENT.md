# Deployment Guide

This guide explains how to deploy the portfolio website to various hosting platforms.

## 🚀 GitHub Pages (Recommended)

### Step 1: Create GitHub Repository
1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `portfolio-website` or similar
3. Make it public for free hosting

### Step 2: Upload Files
1. Clone the repository locally
2. Copy all project files to the repository folder
3. Commit and push to GitHub:
   ```bash
   git add .
   git commit -m "Initial portfolio website"
   git push origin main
   ```

### Step 3: Enable GitHub Pages
1. Go to repository Settings
2. Scroll to "Pages" section
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

### Step 4: Access Your Site
- Your site will be available at: `https://yourusername.github.io/portfolio-website`
- It may take a few minutes to deploy

## 🌐 Netlify

### Method 1: Drag & Drop
1. Go to [Netlify](https://netlify.com)
2. Drag your project folder to the deploy area
3. Get instant live URL

### Method 2: GitHub Integration
1. Connect your GitHub account
2. Select your repository
3. Deploy automatically on every push

## ⚡ Vercel

1. Go to [Vercel](https://vercel.com)
2. Import your GitHub repository
3. Framework preset: "Other"
4. Deploy automatically

## 🔧 Custom Domain (Optional)

### For GitHub Pages
1. Add `CNAME` file with your domain name
2. Update DNS settings with your domain provider
3. Add custom domain in GitHub Pages settings

### For Netlify/Vercel
1. Add custom domain in project settings
2. Update DNS records as instructed

## 📝 Pre-Deployment Checklist

- [ ] All files are properly organized
- [ ] No broken links or images
- [ ] Forms work correctly
- [ ] Mobile responsive design tested
- [ ] All pages load without errors
- [ ] Contact information is updated
- [ ] Social media links are updated
- [ ] README.md is complete

## 🐛 Troubleshooting

### Common Issues
1. **404 Errors**: Check file paths and case sensitivity
2. **CSS Not Loading**: Verify CSS file paths
3. **JavaScript Errors**: Check browser console for errors
4. **Images Not Showing**: Verify image file paths

### Testing
- Test on multiple devices and browsers
- Check mobile responsiveness
- Validate HTML and CSS
- Test all interactive features

## 📊 Performance Optimization

### Before Deployment
- Optimize images (compress if needed)
- Minify CSS and JavaScript (optional)
- Enable gzip compression
- Use CDN for external resources

### After Deployment
- Test loading speeds
- Check mobile performance
- Verify all features work
- Monitor for errors

## 🔄 Updates and Maintenance

### Making Changes
1. Edit files locally
2. Test changes
3. Commit and push to GitHub
4. Changes deploy automatically

### Regular Maintenance
- Update dependencies
- Check for broken links
- Monitor performance
- Update content as needed

## 📞 Support

If you encounter issues:
1. Check the troubleshooting section
2. Review browser console for errors
3. Test locally first
4. Contact support if needed

---

**Happy Deploying! 🚀**
