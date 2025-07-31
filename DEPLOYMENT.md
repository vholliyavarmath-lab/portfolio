# 🚀 Deploy to Vercel - Step by Step Guide

## Prerequisites
- GitHub account
- Vercel account (free at [vercel.com](https://vercel.com))

## Method 1: Deploy via Vercel Dashboard (Recommended)

### Step 1: Upload to GitHub
1. Create a new repository on GitHub
2. Upload all your files to the repository:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `package.json`
   - `vercel.json`
   - `README.md`

### Step 2: Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) and sign up/login
2. Click **"New Project"**
3. Import your GitHub repository
4. Vercel will automatically detect it's a static site
5. Click **"Deploy"**
6. Your site will be live in seconds!

## Method 2: Deploy via Vercel CLI

### Step 1: Install Vercel CLI
```bash
npm install -g vercel
```

### Step 2: Deploy
```bash
# Navigate to your project folder
cd your-portfolio-folder

# Deploy
vercel

# Follow the prompts:
# - Login to Vercel (if not already)
# - Link to existing project or create new
# - Confirm deployment settings
```

## Method 3: Drag & Drop (Quickest)

1. Go to [vercel.com](https://vercel.com)
2. Drag your entire project folder to the Vercel dashboard
3. Vercel will automatically deploy it

## 🎯 Custom Domain (Optional)

After deployment:
1. Go to your project dashboard on Vercel
2. Click **"Settings"** → **"Domains"**
3. Add your custom domain (e.g., `vinayak-portfolio.com`)
4. Follow the DNS configuration instructions

## 📱 Your Live Portfolio

Your portfolio will be available at:
- `https://your-project-name.vercel.app`
- Or your custom domain if you set one up

## 🔄 Updates

To update your live site:
1. Make changes to your files
2. Push to GitHub (if using Method 1)
3. Or run `vercel --prod` (if using Method 2)
4. Your site updates automatically!

## 🎨 Features Added

✅ **Personalized with your name**: Vinayak M Holliyavarmath  
✅ **Modern statistics section**: Animated counters  
✅ **Enhanced contact info**: Phone number added  
✅ **Better typography**: Updated font weights  
✅ **Favicon**: Engineering gear icon  
✅ **Vercel optimized**: Ready for deployment  

## 🚀 Performance Features

- **Fast loading**: Optimized for speed
- **SEO friendly**: Proper meta tags
- **Mobile responsive**: Works on all devices
- **Modern animations**: Smooth interactions
- **Security headers**: Protected against common attacks

---

**Your portfolio is now ready to go live! 🎉** 