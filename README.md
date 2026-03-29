# Haiming Wu — Academic Website

Personal academic website for Haiming Wu, PhD candidate in Economics at University College London.

**Live site:** [haimingecon.github.io](https://haimingecon.github.io)

---

## Site structure

| File | Page |
|------|------|
| `index.html` | Homepage — bio, working papers, education & affiliations |
| `research.html` | Research — papers with collapsible abstracts, presentations |
| `cv.html` | CV summary with downloadable PDF |
| `contact.html` | Contact info, office address, profile links |
| `style.css` | Shared stylesheet |
| `photo.jpg` | Profile photo |
| `cv.pdf` | Downloadable CV |
| `favicon.png` | Browser tab icon |

---

## How to update

### Edit a page
1. Go to the repo on GitHub
2. Click the file you want to edit
3. Click the pencil icon (top right)
4. Make your changes
5. Click **Commit changes**
6. Wait 1–2 minutes, then hard refresh (Ctrl+Shift+R) to see updates

### Add a new paper
In `research.html`, copy this block inside the working in progress section:

```html
<div class="paper-item">
  <p class="paper-title">Your Paper Title</p>
  <p class="paper-authors">with Coauthor Name</p>
  <p class="paper-venue">Work in progress</p>
  <button class="abstract-toggle" onclick="this.classList.toggle('open'); this.nextElementSibling.classList.toggle('open');">
    <span class="arrow">&#9654;</span> Abstract
  </button>
  <p class="abstract-content">Your abstract here.</p>
</div>
```

Also add a short entry in `index.html` inside the working in progress card:

```html
<div style="margin-bottom: 0.8rem;">
  <p class="card-title">Your Paper Title</p>
  <p class="card-meta">with Coauthor Name — Work in progress</p>
</div>
```

### Update your CV
1. Compile your LaTeX CV and save the PDF as `cv.pdf`
2. Go to the repo → Add file → Upload files → upload the new `cv.pdf`
3. Update `cv.html` if any sections changed

### Update your photo
1. Save your new photo as `photo.jpg`
2. Upload it to the repo (it will replace the old one)

### Add a presentation
In `research.html`, add a new entry inside the presentations section:

```html
<div class="paper-item">
  <p class="paper-title">Conference Name (City)</p>
  <p class="paper-venue">Year</p>
</div>
```

---

## Custom domain (optional)

To use a custom domain like `haimingwu.com` instead of `haimingecon.github.io`:

1. Buy a domain from a registrar (Namecheap, Google Domains, etc.)
2. In your repo, go to Settings → Pages → Custom domain → enter your domain
3. At your registrar, add DNS records pointing to GitHub Pages
4. See [GitHub's guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-github-pages) for full instructions

---

## Built with

- HTML + CSS (no frameworks)
- Google Fonts: Cormorant Garamond + Source Sans 3
- Hosted on GitHub Pages
