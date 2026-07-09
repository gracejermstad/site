# Grace Jermstad — Portfolio

Static site. Plain HTML/CSS/JS, no build step.

## ⚠️ Before deploying: add 6 photos
The About page expects six images in the `images/` folder that aren't included here.
Add these files (square .webp, ~560px works well):

- images/about-painting.webp
- images/about-welding.webp
- images/about-hiking.webp
- images/about-exploring.webp
- images/about-michigan.webp
- images/about-cat.webp

Until they're added, those six tiles on the About page will appear blank.
(The hero headshot, `images/about-headshot.webp`, IS included.)

## Structure
- index.html ............ home
- pretium.html .......... case study 01
- nomad.html ............ case study 02
- cece.html ............. more work
- lakeshore.html ........ more work
- littlewren.html ....... more work
- koehler.html .......... more work
- art.html .............. fine art gallery
- about.html ............ about + résumé
- images/ ............... all page images
- favicon.svg

## Deploy (GitHub + Vercel, free)
1. Create a new public GitHub repo (no README/gitignore).
2. Upload the CONTENTS of this folder (not the folder itself) — drag all files + the images/ folder in, Commit.
3. Go to vercel.com → Sign up with GitHub → Add New Project → Import your repo → Deploy.
4. Custom domain: Vercel → Project → Settings → Domains → add gracejermstad.com and www.
   Vercel shows an A record + a CNAME. In Namecheap → Domain → Advanced DNS:
   - DELETE any existing parking / URL-redirect records first (this is the #1 cause of failures).
   - Add Vercel's A record (host @) and CNAME (host www → cname.vercel-dns.com). Save.
   DNS can take a little while to propagate.

To update later: re-upload changed files to GitHub; Vercel redeploys automatically.
(Note: re-uploading does NOT delete files you removed — delete stale files manually in GitHub.)


## Replacing the Little Wren hero
The Little Wren page now expects `images/littlewren-img0.jpg` (higher-res).
Drop your exported JPG in the images/ folder with that exact name.
