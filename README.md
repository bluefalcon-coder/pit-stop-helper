# Pit Stop Helper

A Mario Kart 8 Deluxe build calculator, build recommender, stat lessons, item and driving tips, shortcuts and a build log.

This is an unofficial fan project. It is not made by or connected to Nintendo. Mario Kart is a trademark of Nintendo.

(c) 2026 Swipestars. All rights reserved.

## What is in this folder

- `index.html` is the whole site. It has no other files to load and needs no build step.
- `README.md` is this page.

The site loads two fonts (Archivo and Barlow) from Google Fonts. If they cannot load, it falls back to plain system fonts and still works.

## Put it live with GitHub Pages (website only, no commands)

1. Sign in at https://github.com. Make an account first if you do not have one.
2. Click the **+** at the top right, then **New repository**.
3. Name it `pit-stop-helper`. Choose **Public**. Free GitHub Pages needs a public repository. Click **Create repository**.
4. On the new empty repository page, click **uploading an existing file**. (Or use **Add file**, then **Upload files**.)
5. Drag in `index.html` and `README.md`. The file must be named exactly `index.html`, in lowercase, and must sit at the top level of the repository, not inside a folder.
6. Scroll down and click **Commit changes**.
7. Click **Settings** (the tab near the top of the repository), then **Pages** in the left menu.
8. Under **Build and deployment**, set **Source** to **Deploy from a branch**. Set **Branch** to `main` and the folder to `/ (root)`. Click **Save**.
9. Wait one to two minutes and refresh the Pages settings page. A box at the top says **Your site is live at** and shows the link:

   `https://YOUR-USERNAME.github.io/pit-stop-helper/`

Open that link to check it. Share it with anyone.

## The same thing with commands

Run these in a terminal, inside the folder that holds `index.html`. Replace `YOUR-USERNAME`.

```
git init -b main
git add index.html README.md
git commit -m "Add Pit Stop Helper"
git remote add origin https://github.com/YOUR-USERNAME/pit-stop-helper.git
git push -u origin main
```

Create the empty `pit-stop-helper` repository on github.com first (steps 1 to 3 above), then run the commands, then do steps 7 to 9 to turn on Pages.

If you use the GitHub command line tool (`gh`), this does the repository, the push and the Pages setting:

```
gh repo create pit-stop-helper --public --source=. --push
gh api -X POST repos/YOUR-USERNAME/pit-stop-helper/pages -f "source[branch]=main" -f "source[path]=/"
```

## Updating the site later

Replace `index.html` in the repository with the new version (on github.com: open the file, click the pencil or use **Add file** then **Upload files** with the same name, then **Commit changes**). The live site updates in a minute or two.

## Good to know

- **Saved builds stay in each person's browser.** My Builds, the checklist, the parts you own and your recommender choices are saved on the device that was used. They do not sync between devices or people. If the site address changes, such as moving to a custom domain, saved data does not move with it. The My Builds page has a copy-as-text backup.
- **Share a build:** copy its build code in the calculator, then add `#` and the code to the end of the live link, like `https://YOUR-USERNAME.github.io/pit-stop-helper/#b-13-30-17-4`.
- **Repositories on the free plan are public.** Do not put private information in any file.
- **Getting a 404?** Check that the file is named `index.html` at the top level, that Pages is set to the `main` branch and `/ (root)`, and wait a couple of minutes.
- **Own web address (optional):** in Settings, then Pages, you can add a custom domain once you own one. GitHub explains the DNS steps there.

## Where the numbers come from

Nintendo Life's Mario Kart 8 Deluxe stat tables, Kotaku (Mini-Turbo details), Keen Gamer and Inverse (shortcuts) and Nintendo's patch notes. See the About page on the site for the limits.
