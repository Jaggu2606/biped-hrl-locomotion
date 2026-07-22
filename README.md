# Hierarchical Reinforcement Learning for Collision-Free Locomotion of an Underactuated Biped

Project page for the paper by Jagannath Prasad Sahoo, Saurabh Kumar, Surya Prakash S.K., Abhay Dwivedi, and Amit Shukla (IIT Mandi, CAIR Lab).

## Live site

Once GitHub Pages is enabled (see below), the site will be live at:
`https://Jaggu2606.github.io/biped-hrl-locomotion/`

(rename the repo if you'd prefer a different URL — just swap `biped-hrl-locomotion` below for whatever you pick)

## Deploying with GitHub Pages

1. On GitHub, create a new repository named `biped-hrl-locomotion` under your account
   (**do not** initialize it with a README, .gitignore, or license — this folder already
   has its own git history).
2. From this folder, run:
   ```bash
   git remote add origin https://github.com/Jaggu2606/biped-hrl-locomotion.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
5. Save. The site will be live in a minute or two at `https://Jaggu2606.github.io/biped-hrl-locomotion/`.

## Structure

```
index.html          Main page
css/styles.css       Styles
assets/images/       Gallery, training, results, ablation images + logo
assets/videos/       Demo video (compressed for web, ~2.5MB)
.nojekyll            Tells GitHub Pages not to run Jekyll processing
```

## Notes / things you may want to update

- The gallery/training/results/ablation images were auto-assigned in upload order
  (`gallery_1.jpg`, `gallery_2.jpg`, `training.jpg`, `results_1.jpg`, `results_2.jpg`,
  `ablation.jpg` under `assets/images/`) — swap filenames if any don't match their section.
- The demo video was re-encoded from 72MB to ~2.5MB (720p, H.264) for fast loading;
  the original is untouched if you need the higher-res source.
- The "Code Repository" and "Dataset / Sim Env" buttons in the hero section still point
  to `#` placeholders — update their `href` in `index.html` once those are public.
