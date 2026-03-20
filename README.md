# Parthrajsinh Dabhi - Professional Portfolio

A modern, professional, dark-themed personal portfolio website built with pure HTML, CSS, and JavaScript. Optimized for GitHub Pages deployment with zero dependencies.

## 🎯 Live Demo

Visit: `https://username.github.io` (replace `username` with your GitHub username)

## ✨ Features

✅ **Modern Dark Theme** - Professional cyan and purple gradient accents  
✅ **Fully Responsive** - Mobile, tablet, and desktop optimized  
✅ **Smooth Animations** - Scroll effects, hover interactions, transitions  
✅ **No Dependencies** - Pure HTML, CSS, and JavaScript  
✅ **SEO Optimized** - Semantic HTML, meta tags, proper structure  
✅ **Accessibility** - WCAG compliant, keyboard navigation  
✅ **Fast Loading** - Lightweight, optimized performance  
✅ **Easy Customization** - Clear placeholders and simple structure  

## 📁 File Structure

```
.
├── index.html          # Complete website (all-in-one file)
├── README.md           # This file
├── .gitignore          # Git ignore rules
└── LICENSE             # MIT License
```

## 🚀 Quick Start

### Option 1: Deploy to GitHub Pages (Recommended)

1. **Create a GitHub Repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it: `username.github.io` (replace `username` with your GitHub username)
   - Make it **Public**
   - Click **Create repository**

2. **Upload Files**
   - Click **Add file** → **Upload files**
   - Drag and drop `index.html`, `.gitignore`, and `README.md`
   - Click **Commit changes**

3. **Enable GitHub Pages**
   - Go to **Settings** → **Pages**
   - Select **Deploy from a branch** → **main** → **/ (root)**
   - Click **Save**

4. **Visit Your Site**
   - Your portfolio is live at: `https://username.github.io`

### Option 2: Clone and Push with Git

```bash
# Clone the repository
git clone https://github.com/username/username.github.io.git
cd username.github.io

# Copy files into the directory
# (Place index.html, .gitignore, README.md here)

# Commit and push
git add .
git commit -m "Initial portfolio commit"
git push origin main
```

### Option 3: Local Testing

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js
npx http-server
```

Then open `http://localhost:8000` in your browser.

## 📝 Customization Guide

### Update Your Information

Open `index.html` and find these sections:

**1. Hero Section (Line ~150)**
```html
<h1 class="hero-title">
    <span class="gradient-text">Parthrajsinh Dabhi</span>
</h1>
<p class="hero-subtitle">Full-Stack Developer | React Specialist | Problem Solver</p>
```
Replace with your name and title.

**2. About Section (Line ~250)**
Update the three paragraphs with your background and experience.

**3. Projects Section (Line ~320)**
Update project titles, descriptions, tech stacks, and GitHub links.

**4. Skills Section (Line ~430)**
Add/remove skills in each category.

**5. Contact Section (Line ~530)**
Update email, phone, LinkedIn, and GitHub URLs.

### Customize Colors

Find the CSS variables at the top of `<style>` (Line ~10):

```css
--color-accent-cyan: #00D9FF;      /* Primary accent */
--color-accent-purple: #A855F7;    /* Secondary accent */
--color-accent-blue: #3B82F6;      /* Blue accent */
```

**Popular Color Combinations:**

**Professional Blue:**
```css
--color-accent-cyan: #0EA5E9;
--color-accent-purple: #3B82F6;
--color-accent-blue: #1E40AF;
```

**Vibrant Green:**
```css
--color-accent-cyan: #10B981;
--color-accent-purple: #34D399;
--color-accent-blue: #059669;
```

**Warm Orange:**
```css
--color-accent-cyan: #F97316;
--color-accent-purple: #FB923C;
--color-accent-blue: #EA580C;
```

### Add a Profile Picture

1. Upload an image to your repository (e.g., `profile.jpg`)
2. Find the hero section and add:
```html
<img src="profile.jpg" alt="Your Name" style="width: 200px; height: 200px; border-radius: 50%; border: 3px solid var(--color-accent-cyan); object-fit: cover;">
```

## 🌐 Deploy to Custom Domain

### Step 1: Purchase Domain
- [Namecheap](https://www.namecheap.com/)
- [GoDaddy](https://www.godaddy.com/)
- [Google Domains](https://domains.google/)

### Step 2: Configure DNS

Add these A records to your domain's DNS settings:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

Or add CNAME record:
```
www → username.github.io
```

### Step 3: Update GitHub Pages

1. Go to **Settings** → **Pages**
2. Enter your domain under "Custom domain"
3. Check **Enforce HTTPS**
4. Click **Save**

### Step 4: Wait for DNS Propagation

DNS changes can take 5 minutes to 48 hours. Check status at [whatsmydns.net](https://www.whatsmydns.net/)

## 📱 Responsive Design

The portfolio is fully responsive:
- **Desktop** (1200px+): Full layout with side-by-side sections
- **Tablet** (768px - 1199px): Adjusted grid layout
- **Mobile** (Below 768px): Single column with hamburger menu
- **Small Mobile** (Below 480px): Optimized spacing and font sizes

## ♿ Accessibility

- Semantic HTML structure
- Proper color contrast ratios
- Keyboard navigation support
- Focus indicators on interactive elements
- Screen reader friendly

## 🔒 Privacy & Security

- No external API calls
- No tracking or analytics
- No form submissions (contact info is static)
- HTTPS ready for GitHub Pages
- No sensitive data stored

## 🎨 Sections Included

1. **Navigation** - Fixed navbar with smooth scroll links
2. **Hero** - Eye-catching introduction with code window
3. **About** - Professional summary with stats
4. **Projects** - Featured projects with tech stacks
5. **Skills** - Organized by category
6. **Contact** - Email, phone, location, social links
7. **Footer** - Copyright information

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📊 Performance

- **File Size**: ~50KB (single HTML file)
- **Load Time**: < 1 second
- **Lighthouse Score**: 95+
- **No Dependencies**: Pure HTML/CSS/JavaScript

## 🐛 Troubleshooting

**Site not showing?**
- Wait 1-2 minutes for GitHub Pages to deploy
- Clear browser cache (Ctrl+Shift+Delete)
- Check repository is public
- Verify GitHub Pages is enabled in Settings

**Styles look broken?**
- Hard refresh browser (Ctrl+Shift+R)
- Check all CSS is in the `<style>` tag
- Verify no typos in CSS variable names

**Links not working?**
- Ensure GitHub URLs are complete (https://github.com/...)
- Check email link format: `mailto:your@email.com`
- Test in new browser tab

**Mobile menu not working?**
- Check browser console for JavaScript errors
- Verify hamburger menu HTML is present
- Test on actual mobile device

## 📚 Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [HTML Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

**Parthrajsinh Dabhi**
- Email: parthdabhi207@gmail.com
- LinkedIn: [linkedin.com/in/parthrajsinhdabhi](https://linkedin.com/in/parthrajsinhdabhi)
- GitHub: [github.com/Parthrajsinh-Dabhi](https://github.com/Parthrajsinh-Dabhi)

## 🙏 Support

If you find this template helpful, please consider:
- ⭐ Starring the repository
- 🔄 Sharing with others
- 💬 Providing feedback

---

**Happy building! 🚀**

For detailed customization guide, see the comments in `index.html`.
