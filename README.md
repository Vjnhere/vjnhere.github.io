# vjn-portfolio

Personal site for SEMICON India 2026. Static, no build step.

## Folder layout

```
vjn-portfolio/
├─ index.html                  main site
├─ qr.html                     QR generator (open after the site is live)
├─ .nojekyll                   stops GitHub Pages from ignoring files
└─ assets/
   ├─ img/profile.jpg          headshot
   ├─ files/Vijayan_V_Resume.pdf   <-- put your resume here, exact name
   └─ projects/
      ├─ nand/1.png 2.png 3.png    <-- 3D NAND carousel images
      └─ m3d/1.png 2.png 3.png     <-- M3D carousel images
```

Images: PNG or JPG, landscape, roughly 1600×900. If you rename the files,
change the `src` in index.html to match. More than three per project — copy a
`<div class="slide">…</div>` line and add `4.png`.

## Publish on GitHub Pages

1. Sign in at github.com → New repository → name it `vjnhere.github.io` →
   Public → Create.
2. On the repo page: **Add file → Upload files**. Drag the *contents* of this
   folder in (index.html at the top level, not the folder itself). Commit.
3. Settings → Pages → Source: **Deploy from a branch**, Branch: `main`, folder
   `/ (root)` → Save.
4. Wait 1–2 minutes. Site is live at `https://vjnhere.github.io/`.

If you name the repo something else, e.g. `portfolio`, the link becomes
`https://vjnhere.github.io/portfolio/` and you must keep the trailing slash.

## QR code

Open `https://vjnhere.github.io/qr.html`, paste the site link, press Make,
save the image. Print at 5 cm or larger, matte paper, with a line of text under
it so people know what they are scanning.

Test it on two phones before you leave, on mobile data with WiFi off.
