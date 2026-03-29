# Your Academic Website

A clean, professional personal website for an Economics PhD, ready to deploy on GitHub Pages.

---

## 📁 Files included

| File              | Purpose                        |
|-------------------|--------------------------------|
| `index.html`      | Homepage (bio, working papers, news) |
| `research.html`   | Full research & publications page |
| `cv.html`         | CV summary + downloadable PDF  |
| `contact.html`    | Contact info & academic profiles |
| `style.css`       | All styling (shared across pages) |
| `README.md`       | This file                      |

---

## 🚀 How to deploy on GitHub Pages (step by step)

### Step 1: Create a GitHub account
- Go to [github.com](https://github.com) and sign up (free).

### Step 2: Create a new repository
1. Click the **+** button (top right) → **New repository**
2. Name it exactly: `yourusername.github.io`  
   (replace `yourusername` with your actual GitHub username)
3. Set it to **Public**
4. **Do NOT** check "Add a README file" (we already have one)
5. Click **Create repository**

### Step 3: Upload your site files
1. On the repository page, click **"uploading an existing file"** link
2. Drag and drop ALL the files from this folder:
   - `index.html`
   - `research.html`
   - `cv.html`
   - `contact.html`
   - `style.css`
   - Your `photo.jpg` (when ready)
   - Your `cv.pdf` (when ready)
3. Write a commit message like "Initial site upload"
4. Click **Commit changes**

### Step 4: Enable GitHub Pages
1. Go to your repository **Settings** (tab at the top)
2. In the left sidebar, click **Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose the **main** branch and **/ (root)** folder
5. Click **Save**

### Step 5: Visit your site!
- Wait 1–2 minutes, then go to: `https://yourusername.github.io`
- Your site is live!

---

## ✏️ How to customize

### Replace placeholder text
Open each `.html` file and search for these placeholders to replace:

- `Your Name` → your real name
- `University Name` → your university
- `your.email@university.edu` → your email
- `[Field 1]` and `[Field 2]` → your research fields
- `YN` (in the photo placeholder) → your initials
- All paper titles, coauthor names, dates, etc.

### Add your photo
1. Save a professional headshot as `photo.jpg` in the same folder
2. In `index.html`, find this line:
   ```html
   <div class="hero-photo-placeholder">YN</div>
   ```
3. Replace it with:
   ```html
   <img src="photo.jpg" alt="Your Name" class="hero-photo">
   ```

### Add your CV PDF
1. Save your CV as `cv.pdf` in the same folder
2. Upload it to GitHub alongside your other files
3. The download button on the CV page will work automatically

### Update your site
After making changes to any file:
1. Go to your repository on GitHub
2. Navigate to the file you changed
3. Click the **pencil icon** (edit) to edit directly on GitHub  
   — OR re-upload the modified file
4. Commit changes → site updates in ~1 minute

---

## 💡 Tips

- **Custom domain**: You can use a custom domain (e.g., `janedoe.com`) — see [GitHub's guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-github-pages)
- **Google Scholar link**: Update the footer links to point to your actual profiles
- **Job market**: The homepage includes a job market notice — remove it when not on the market
- **Mobile-friendly**: The site is fully responsive and works on phones and tablets
