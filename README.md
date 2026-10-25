# Tasting the Gulf

Group blog for our class project, How Food Tells a Story of Culture, History, and Identity, on Dubai and the Khaleeji region. Plain HTML and CSS, no build step.

## Structure

```
index.html              Home: intro, reflection cards, About Us
final-project.html      Placeholder for the final presentation
posts/
  abu-naji-aarav.html   Aarav's restaurant reflection
  kartheek.html         Placeholder for Kartheek
  tanish.html           Placeholder for Tanish
css/style.css           All styles
images/                 Photos (compressed JPGs)
```

## Deploy on GitHub Pages

1. Create a new public repo on GitHub, for example `khaleeji-blog`.
2. From this folder:
   ```
   git init
   git add .
   git commit -m "Initial blog"
   git branch -M main
   git remote add origin https://github.com/<your-username>/khaleeji-blog.git
   git push -u origin main
   ```
3. On GitHub, open the repo's Settings, then Pages. Under "Build and deployment", set Source to "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
4. After a minute or two the site is live at `https://<your-username>.github.io/khaleeji-blog/`.
   Your post is at `https://<your-username>.github.io/khaleeji-blog/posts/abu-naji-aarav.html`.

## Adding a teammate's reflection

1. Put their photos in `images/` (keep them under about 500 KB each).
2. Open `posts/kartheek.html` or `posts/tanish.html`, delete the "Coming soon" box, and add their text using the same tags as `abu-naji-aarav.html`.
3. In `index.html`, replace that card's `<div class="placeholder">Coming soon</div>` with an `<img>` of one of their photos, and update the card title and summary.
4. Commit and push. Pages updates automatically.
