# Charlesee Han's Portfolio Website

This is the portfolio website for author Charlesee Han, showcasing the Robo Ninja and Monarch Realm book series.

## 📁 Folder Structure

```
/Users/user/Desktop/Charles/
├── index.html                    # Main website file
├── images/
│   ├── book-covers/             # Book cover images (7 images needed)
│   │   ├── robo-ninja.jpg
│   │   ├── robo-ninja-2.jpg
│   │   ├── robo-ninja-3.jpg
│   │   ├── robo-ninja-4.jpg
│   │   ├── monarch-realm.jpg
│   │   ├── monarch-realm-2.jpg
│   │   └── monarch-realm-3.jpg
│   └── gallery/                 # Gallery images (6 images needed)
│       ├── gallery-1.jpg
│       ├── gallery-2.jpg
│       ├── gallery-3.jpg
│       ├── gallery-4.jpg
│       ├── gallery-5.jpg
│       └── gallery-6.jpg
├── vercel.json                   # Vercel configuration
└── README.md                     # This file
```

## 📸 Next Steps: Add Your Images

### Book Covers (7 images needed)

Place your book cover images in the `images/book-covers/` folder with these exact filenames:

1. `robo-ninja.jpg` - Robo Ninja (Book 1)
2. `robo-ninja-2.jpg` - Robo Ninja 2
3. `robo-ninja-3.jpg` - Robo Ninja 3
4. `robo-ninja-4.jpg` - Robo Ninja 4
5. `monarch-realm.jpg` - The Monarch Realm
6. `monarch-realm-2.jpg` - The Monarch Realm 2
7. `monarch-realm-3.jpg` - The Monarch Realm 3

**Image specs:**
- Format: JPG or PNG
- Recommended size: 600-800px width
- Aspect ratio: Portrait (book cover shape)

### Gallery Images (6 images needed)

Place your gallery/artwork images in the `images/gallery/` folder:

1. `gallery-1.jpg`
2. `gallery-2.jpg`
3. `gallery-3.jpg`
4. `gallery-4.jpg`
5. `gallery-5.jpg`
6. `gallery-6.jpg`

**Image specs:**
- Format: JPG or PNG
- Recommended size: 800-1200px width
- Aspect ratio: Square works best

## 🚀 Deploy to Vercel

### **RECOMMENDED: Method 1 - Web Interface (Easiest!)**

This is the simplest way to deploy - no installation or terminal commands needed!

1. Go to https://vercel.com
2. Sign up or login (you can use email, GitHub, or GitLab)
3. Click "Add New..." → "Project"
4. **Drag and drop** the entire `/Users/user/Desktop/Charles` folder into the browser
   - OR click "Browse" and select the folder
5. Vercel will automatically upload ALL files (HTML + all images)
6. Click "Deploy"
7. Wait 20-60 seconds
8. Get your live URL! (e.g., `charlesee-han.vercel.app`)

**That's it!** Your website is now live on the internet. Vercel hosts everything - you can turn off your computer and the site stays online.

### Method 2 - Vercel CLI (Advanced Users)

If you prefer using the terminal:

1. Install Vercel CLI: `npm install -g vercel`
2. Open Terminal and navigate to this folder: `cd /Users/user/Desktop/Charles`
3. Run: `vercel`
4. Follow the prompts to login and deploy
5. Your site will be live!

### Method 3 - GitHub Integration (For Auto-Updates)

If you want automatic deployments when you make changes:

1. Create a GitHub repository
2. Push this folder to GitHub
3. In Vercel, click "Import Git Repository"
4. Select your GitHub repo
5. Every time you update files on GitHub, Vercel auto-deploys!

## ✅ Before Deploying

Make sure you've added all images to the correct folders:
- ✅ 7 book cover images in `images/book-covers/`
- ✅ 6 gallery images in `images/gallery/`

You can test locally by opening `index.html` in a web browser.

## 📊 How Deployment Works

When you deploy to Vercel:
1. ALL files in this folder get uploaded to Vercel's servers
2. Your website runs from Vercel's fast global CDN
3. Your laptop doesn't need to stay on - the site is hosted by Vercel
4. Images are served from Vercel's servers (not your computer)
5. Updates: Just re-deploy the folder to update the live site

## 💰 Cost

**FREE!** Vercel's free tier is perfect for static websites like this.

## 🎨 Customization

To update the website after deployment:
1. Edit `index.html` locally
2. Add/replace images in the `images/` folders
3. Re-deploy using your chosen method
4. Changes appear live within 30-60 seconds

## 📝 Notes

- The website is mobile-responsive and works on all devices
- Images use lazy loading for better performance
- Book 8 placeholder can be updated later when ready
- Fan mail form shows a "Thank you" message (no backend required)

---

**Need help?** If you have questions about deploying, just ask!
