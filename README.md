# The Stat Man Website

A clean, professional website for hosting your football statistics and analysis articles.

## 📁 Files Included

- `index.html` - Your homepage with article listings
- `styles.css` - Styling for the homepage
- `article-template.html` - Template for creating new articles
- `article-styles.css` - Styling for article pages

## 🚀 How to Add New Articles

### Step 1: Create a New Article
1. Make a copy of `article-template.html`
2. Rename it (e.g., `article-1.html`, `article-2.html`, etc.)
3. Open the file and edit:
   - Change the `<title>` tag
   - Update the date in the article meta section
   - Replace "Your Article Title Goes Here" with your actual title
   - Replace the template content with your analysis

### Step 2: Add to Homepage
1. Open `index.html`
2. Find the articles grid section
3. Copy one of the existing article cards
4. Update:
   - The date
   - The category (Premier League, La Liga, Player Analysis, etc.)
   - The article title
   - The preview text
   - The link (`href="article-1.html"` → change to match your new file name)

## 📝 Writing Your Articles

Your articles can include:
- **Paragraphs** - Just write normally
- **Headings** - Use `<h2>Section Title</h2>` for main sections
- **Lists** - For bullet points or numbered stats
- **Quotes** - Use `<blockquote>` for highlighted statistics
- **Bold text** - Use `<strong>key stat</strong>` to emphasize numbers

No character limits! Write as much as you need.

## 🌐 How to Host for FREE

### Option 1: GitHub Pages (Recommended - Easiest)

1. **Create a GitHub account** at github.com (if you don't have one)

2. **Create a new repository**:
   - Click "New repository"
   - Name it: `statman-website` (or any name you want)
   - Make it Public
   - Click "Create repository"

3. **Upload your files**:
   - Click "uploading an existing file"
   - Drag and drop ALL your website files
   - Click "Commit changes"

4. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Under "Source", select "main" branch
   - Click Save

5. **Get your website link**:
   - Your site will be live at: `https://yourusername.github.io/statman-website/`
   - Share this link on X!

### Option 2: Netlify (Also Free)

1. Go to netlify.com
2. Sign up for free
3. Drag and drop your website folder
4. Get your free link instantly!

## 📱 Sharing on X

Once your site is live:
1. Write your normal X post/thread
2. At the end, add: "Full analysis: [your-website-link]"
3. People can click to read the complete breakdown!

## ✏️ Making Changes

To update your website:
- Edit the HTML files
- Save them
- Re-upload to GitHub/Netlify
- Changes appear automatically!

## 💡 Tips

- Keep article file names simple: `article-1.html`, `salah-stats.html`, etc.
- Update the homepage whenever you add a new article
- Categories can be anything: Premier League, La Liga, Serie A, Player Analysis, etc.
- The website works great on mobile automatically!

## 🎨 Customization

Want to change colors? Edit the `:root` section in `styles.css` and `article-styles.css`:
- `--color-primary` - Main accent color (currently green)
- `--color-accent` - Secondary color (currently blue)
- `--color-bg` - Background color

---

Need help? DM on X: @stat_man2
