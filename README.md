# Lucian Sharpe Portfolio Site

This folder is a standalone static website ready to upload to a GitHub Pages repository.

## Replace images

- Placeholder images live in `images/`.
- Replace each `.svg` placeholder with your final image file, or keep the filename the same so you do not need to update the HTML.
- If you use a different filename, update the matching `<img src="...">` tag in the relevant project page inside `projects/`.

## Edit text

- Homepage content is in `index.html`.
- Resume content is in `resume.html`.
- Case study content is in the files inside `projects/`.
- Shared styling is in `styles/main.css`.
- Small shared behavior, including the mobile menu, is in `scripts/main.js`.

## Add the resume PDF

- Put your final resume PDF at `assets/Lucian_Sharpe_Resume.pdf`.
- A placeholder PDF is already included so the download link works immediately.
- Replacing the file with your final PDF will update all existing download links automatically.

## Upload to GitHub Pages

1. Create or open the GitHub repository you want to use for the site.
2. Upload the contents of this folder, not the parent `portfolio-site` folder itself, to the repo root.
3. In GitHub, open `Settings > Pages`.
4. Set the deployment source to the main branch root.
5. Confirm the custom domain is `lucian-sharpe.com`.
6. Keep the root `CNAME` file in the repo so GitHub Pages preserves the custom domain.

After Pages finishes deploying, the site should load from your custom domain with the same relative links used locally.
