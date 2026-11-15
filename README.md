# Arnav Kolluru — Academic Website

A complete, static, single-page academic website styled after the simple layout of kevin-m-zhang.github.io.

## Files

- `index.html` — the entire website (no coding environment or build tools required).
- `Arnav_Kolluru_CV.pdf` — your **original uploaded CV PDF**, linked from the navigation, introduction, and bottom of the page.
- `.nojekyll` — tells GitHub Pages to serve the HTML as-is.

## Publish at https://YOUR-USERNAME.github.io/

1. Sign in to [GitHub](https://github.com/). Create an account if needed.
2. Open [Create a new repository](https://github.com/new).
3. Name the repository **YOUR-USERNAME.github.io**, replacing `YOUR-USERNAME` with your **exact GitHub username** (not your name unless it is your username).
4. Set repository visibility to **Public**, then create the repository.
5. Choose **Add file → Upload files** and upload `index.html`, `Arnav_Kolluru_CV.pdf`, and `.nojekyll` (from the unzipped folder). `README.md` is optional. If GitHub hides `.nojekyll`, it's okay to omit; this simple site works without it too.
6. Click **Commit changes** on the `main` branch.
7. Go to **Settings → Pages**. Under **Build and deployment**, set **Source: Deploy from a branch**, **Branch: main**, and **Folder: /(root)**, then click **Save**.
8. Visit `https://YOUR-USERNAME.github.io/`. It may take several minutes for GitHub Pages to publish the site.
9. Test that the **CV (PDF)** link opens the PDF in a new tab.

If you already use a repository named `YOUR-USERNAME.github.io`, you can upload these files there instead. The relative PDF link works with user sites and project sites.

## Customize

- All page text is in `index.html`; it can be edited in GitHub by opening the file and clicking the pencil icon.
- The profile area currently shows the initials **AK**, because no headshot was supplied. You can replace it with your portrait later. Within `index.html`, replace the `div` with class `portrait` by an image like this: `<img class="portrait" src="profile.jpg" alt="Portrait of Arnav Kolluru">`, and upload `profile.jpg` alongside `index.html`. The CSS keeps the image size; you may also add `object-fit: cover;` in the `.portrait` rule.
- To update your CV later, replace `Arnav_Kolluru_CV.pdf` with a newer PDF using the exact same filename.

## Privacy note

The site and its linked PDF are **public** once published. Your uploaded PDF contains an email address and a phone number. Review the PDF before publishing if you don't want these details public.

## Source accuracy

The text on this site was adapted from the uploaded `Arnav_Kolluru_Research_CV.docx`. Manuscripts are labeled as manuscripts; accepted and published items are identified separately. No external manuscript links were invented.
