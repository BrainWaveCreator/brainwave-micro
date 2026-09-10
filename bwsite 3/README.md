# Brainwave Studio — landing site

Static site. No build step, no dependencies.

## Files
```
index.html              the whole site
assets/logos/*.png      client logos + the Brainwave mark
```

## Deploy to Vercel

**Drag and drop (easiest)**
1. Go to https://vercel.com/new
2. Drag this whole folder onto the page
3. Framework preset: **Other**. Leave build command and output directory empty.
4. Deploy.

**Or from the terminal**
```bash
npm i -g vercel
cd bwsite
vercel          # preview
vercel --prod   # live
```

## Adding work
Open `index.html` and find the `Selected work` section. There is a comment block
with instructions. Copy one `<a class="piece">` block, change the `href` to the
real link, and edit the title, meta line and description. Delete any block you
do not need.

## Notes
- Fonts load from Google Fonts. Everything else is local.
- The Zmode and Brainwave marks were supplied in white and recolored to ink so
  they read on the light background. Originals untouched.
- The MGI logo arrived as a JPEG on a white box; the white was knocked out so it
  sits flush with the other logos.
