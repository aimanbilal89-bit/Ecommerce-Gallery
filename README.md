# ShopEase - Responsive E-Commerce Product Gallery

## Web Engineering Lab 8

This project completes Lab Task 1 and provides the files required for Lab Task 2.

### Files
- `index.html` - page structure and six product cards
- `style.css` - styling, responsive CSS Grid, and hover animations
- `README.md` - project information and Git instructions

### Task 1 requirements
- Product gallery created with CSS Grid.
- Uses `repeat(auto-fit, minmax(250px, 1fr))`.
- Uses `minmax()` and `auto-fit` so the columns adjust automatically.
- The product grid does not need an explicit media query to change its number of columns.
- Product cards have hover animations using `transform` and `transition`.

### Run the page
1. Open this folder in Visual Studio Code.
2. Open `index.html`.
3. Right-click and choose **Open with Live Server** if the Live Server extension is installed.
   Alternatively, open `index.html` directly in a web browser.

### Upload to GitHub (Task 2)
Open the VS Code terminal in this project folder and run:

```bash
git init
git status
git add .
git commit -m "Create responsive ecommerce product gallery"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Replace the remote URL with the HTTPS URL of your own GitHub repository.

If the GitHub repository already contains a README and Git reports unrelated histories, run:

```bash
git pull origin main --allow-unrelated-histories
```

Resolve any merge message or conflicts if prompted, then push:

```bash
git push -u origin main
```

### Verify
Refresh your GitHub repository page. It should contain `index.html`, `style.css`, and `README.md`.
