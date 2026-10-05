# 🎓 Congratulations, Rutvi

## 1 · Upload the film to YouTube (Unlisted)

1. On YouTube → **Create → Upload video** and choose your final 4K file.
2. **Audience:** choose **"No, it's not made for kids"**. (Videos marked "made for kids" have limited playback on other websites.)
3. **Visibility:** choose **Unlisted**, *not* Private.
   Unlisted means it isn't on your channel page or in search. Only people with the link can watch. A Private video won't play on the website.
4. Wait for YouTube to finish processing. HD is ready first and **4K** usually arrives a little later.
5. Click **Share → Copy** to copy the link.

> **Music check:** if the film contains a copyrighted song (a Bollywood track, even as a piano cover), YouTube may add a claim.
> Usually it still plays, but sometimes the song is muted or embedding is blocked. **YouTube Studio → Content → Restrictions** shows this after upload.

## 2 · Paste the link into the website

Open `index.html` in any text editor (TextEdit, Notepad, VS Code, or later GitHub's ✏️ edit button). Near the bottom, in the `SETTINGS` box:

```js
const YOUTUBE_LINK = "https://youtu.be/AbCdEfGhIjK";
```

Any YouTube link format works. The film card on the page automatically uses the video's YouTube thumbnail.
*(Tip: set a custom thumbnail in YouTube Studio and the page will use it.)*

## 3 · Put it on GitHub (about 5 minutes)

1. On github.com: top-right **+ → New repository** → name it `rutvi-graduation` → **Public** → **Create repository**.
2. Click **uploading an existing file**, drag in `index.html`, `README.md` and the `assets` folder → **Commit changes**.
3. **Settings → Pages** → Source: **Deploy from a branch** · Branch: **main** · Folder: **/ (root)** → **Save**.
4. After 1–2 minutes your link appears at the top of that page:
   **`https://YOUR-GITHUB-USERNAME.github.io/Grarutvication/`**

**Optional, for a nice Instagram link preview:** in `index.html`, replace `YOUR-GITHUB-USERNAME` in the `og:image` line
with your GitHub username and commit.

## 4 · Test, then send

Open the link on your phone in a **private/incognito** window so you see it the way she will. Tap **Watch the film**, and check the sound and full screen.
---
