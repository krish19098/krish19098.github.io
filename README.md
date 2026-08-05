# Gokul Krishnan N — Product Portfolio

Ready to deploy. All links are wired, all files included.

## Files (keep all 5 in the same folder)
```
index.html     the site
photo.jpg      hero portrait
resume.pdf     linked from nav, hero, contact, footer
zomato.pdf     linked from the Zomato case study + footer
blinkit.pdf    linked from the Blinkit case study + footer
```

## Test locally
Double-click `index.html`. Click the Résumé button and both
"Read case study" buttons — all three PDFs should open.

## Deploy (free, ~3 minutes)
1. github.com → **+** → **New repository**
2. Name it exactly **`krish19098.github.io`**, set **Public**, click **Create**
3. Click **uploading an existing file**, drag in all 5 files, **Commit changes**
4. **Settings** → **Pages** → Source: **Deploy from a branch**,
   Branch: **main**, folder: **/ (root)** → **Save**
5. Wait 1–2 min → live at **https://krish19098.github.io**

First deploy can take up to 5 minutes. If you see a 404, wait and
hard-refresh (Ctrl+Shift+R) before assuming something broke.

## Updating later
Upload the changed file to the repo again — it redeploys in about a minute.

## Once live
Add `https://krish19098.github.io` to your résumé header and LinkedIn profile.

## Swapping a PDF
Replace the file, keeping the same filename (`resume.pdf`, `zomato.pdf`,
`blinkit.pdf`). No code changes needed.

## Responsiveness
Verified 280px (Galaxy Fold) → 2560px (ultrawide): no horizontal overflow,
and every interactive element meets the 44px touch target on phones/tablets.
Touch rules are gated behind `pointer:coarse`, so desktop keeps its slim
slider rail while mobile gets a 44px hit area.
