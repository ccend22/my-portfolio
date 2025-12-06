# How to Add Your Projects to the Portfolio

## Quick Steps

### 1. Update GitHub Links
Replace the placeholder GitHub URLs in `index.html` with your actual repository links:

**Find these lines in index.html:**
- Line ~122: Barbershop Website GitHub link
- Line ~148: Barcode Scanner GitHub link  
- Line ~172: Weather App GitHub link

**Replace with your actual GitHub URLs:**
```html
<!-- Example -->
<a href="https://github.com/endicikalleshi/your-project-name" target="_blank">
```

### 2. Add Live Demo Links

For web projects (Barbershop Website, Weather App), you can host them on:

#### Option A: Netlify (Recommended - Free)
1. Push your project to GitHub
2. Go to [netlify.com](https://netlify.com)
3. Sign up/login with GitHub
4. Click "New site from Git"
5. Select your repository
6. Deploy! You'll get a URL like: `your-project.netlify.app`
7. Replace the demo link in index.html with this URL

#### Option B: Vercel (Free)
1. Push your project to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Sign up/login with GitHub
4. Click "New Project"
5. Import your repository
6. Deploy! You'll get a URL like: `your-project.vercel.app`

#### Option C: GitHub Pages (Free)
1. Go to your repository on GitHub
2. Click Settings → Pages
3. Select your branch (usually `main`)
4. Save! Your site will be at: `username.github.io/repository-name`

### 3. For Mobile Apps (Barcode Scanner)

If your app is published:
- **iOS**: Link to App Store: `https://apps.apple.com/app/your-app`
- **Android**: Link to Play Store: `https://play.google.com/store/apps/details?id=your.app`

If not published yet:
- You can link to a demo video on YouTube
- Or link to screenshots/GIFs showing the app in action
- Or just keep the GitHub link

### 4. Example of Updated Links

```html
<!-- Barbershop Website -->
<a href="https://github.com/endicikalleshi/barbershop-website" target="_blank">
  <span>🔗</span> GitHub
</a>
<a href="https://barbershop-demo.netlify.app" target="_blank">
  <span>🌐</span> Live Demo
</a>

<!-- Weather App -->
<a href="https://github.com/endicikalleshi/weather-app" target="_blank">
  <span>🔗</span> GitHub
</a>
<a href="https://weather-app-demo.vercel.app" target="_blank">
  <span>🌐</span> Live Demo
</a>
```

## Tips

- **Make sure your repositories are public** so people can see your code
- **Add a README.md** to each project explaining what it does
- **Keep your live demos updated** when you make changes
- **Test all links** after updating to make sure they work

## Need Help?

If you need help deploying your projects, check out:
- [Netlify Documentation](https://docs.netlify.com/)
- [Vercel Documentation](https://vercel.com/docs)
- [GitHub Pages Guide](https://pages.github.com/)


