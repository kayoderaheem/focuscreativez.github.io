# Photography Portfolio Website

A professional photography portfolio website with a clean, cinematic design.

## 🚀 Deploy to GitHub Pages

Follow these steps to host your website for FREE on GitHub Pages:

### Step 1: Create a GitHub Account
If you don't have one already, go to [github.com](https://github.com) and sign up.

### Step 2: Create a New Repository
1. Click the "+" icon in the top right corner
2. Select "New repository"
3. Name it: `your-username.github.io` (replace `your-username` with your actual GitHub username)
   - Example: If your username is `johnsmith`, name it `johnsmith.github.io`
4. Make it **Public**
5. Check "Add a README file"
6. Click "Create repository"

### Step 3: Upload Your Website File
1. In your repository, click "Add file" → "Upload files"
2. Drag and drop the `index.html` file (or click to select it)
3. Scroll down and click "Commit changes"

### Step 4: Enable GitHub Pages
1. Go to your repository settings (click "Settings" tab)
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Under "Branch", select "main" and "/ (root)"
5. Click "Save"

### Step 5: Access Your Website
After a few minutes, your website will be live at:
```
https://your-username.github.io
```

## ✏️ Customize Your Website

Open `index.html` in any text editor and update:

### 1. Logo and Name
Find and replace:
- `<div class="logo-icon">S</div>` - Change "S" to your initial
- `<div class="logo-name">YOUR NAME</div>` - Add your name

### 2. About Page
Search for "Your Name" and replace with your actual information:
- Name
- Location
- Biography text

### 3. Contact Information
Update the contact section:
- Email: `contact@yourname.com`
- Phone: `+1 (555) 123-4567`
- Location: `Los Angeles, California`

### 4. Images
Replace the Unsplash URLs with your own images:
- Upload your photos to a service like [Imgur](https://imgur.com) or [Cloudinary](https://cloudinary.com)
- Replace the image URLs in the HTML file

**Image sections to update:**
- Homepage carousel (3 images)
- About page portrait
- Gallery pages (6 images each for: Head Shots, Real Estate, Portrait, Places)

### 5. Page Title
Change `<title>Your Name Photography</title>` to your actual name

## 📸 Adding Your Own Images

### Option 1: Use Image Hosting Services
1. **Imgur** (Free)
   - Upload image at [imgur.com](https://imgur.com)
   - Right-click image → "Copy image address"
   - Paste URL in `index.html`

2. **Cloudinary** (Free tier available)
   - More professional option
   - Better for high-quality images

### Option 2: Host Images in GitHub Repository
1. Create an `images` folder in your repository
2. Upload your photos there
3. Reference them as: `./images/yourphoto.jpg`

## 🎨 Color Customization

To change the color scheme, edit the CSS in the `<style>` section:
- Background: Search for `background-color: #000;` (black)
- Text: Search for `color: #fff;` (white)
- Accents: Modify button and overlay colors

## 📱 Mobile Responsive

The website is already mobile-responsive and will work beautifully on:
- Desktop computers
- Tablets
- Smartphones

## 🔧 Technical Details

- **Framework**: Pure HTML, CSS, and JavaScript (no dependencies)
- **Size**: ~20KB (very fast loading)
- **Compatible**: All modern browsers
- **No build process**: Just upload and go!

## 💡 Tips

1. **Optimize Images**: Compress your images before uploading to improve load times
   - Use [TinyPNG](https://tinypng.com) or [Squoosh](https://squoosh.app)
   - Recommended size: 1920px wide for hero images, 800-1200px for gallery

2. **SEO**: Update the `<title>` tag and add meta descriptions for better search engine visibility

3. **Custom Domain**: You can connect a custom domain (like `yourname.com`) to GitHub Pages:
   - Go to repository Settings → Pages
   - Add your custom domain
   - Follow GitHub's DNS setup instructions

4. **Updates**: Whenever you want to update your website:
   - Edit the `index.html` file
   - Commit and push changes
   - Changes will appear live in a few minutes

## 📞 Need Help?

- GitHub Pages Documentation: [docs.github.com/pages](https://docs.github.com/pages)
- HTML/CSS Help: [w3schools.com](https://w3schools.com)

## 🎉 You're Done!

Your professional photography portfolio is now live on the internet!

Share your website: `https://your-username.github.io`
