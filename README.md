# For Vishalaxi 💌

A single-page proposal experience for mobile: black bg with glowing falling
flowers → cursive intro → heartfelt build-up → proposal (NO button dodges
away) → hug → white love letter → Spotify playlist link.

Everything lives in **`index.html`** plus one optional **`assets/music.mp3`**.

---

## Before you send it

### 1. Add your song (required for music)

1. Create a folder called `assets` next to `index.html` (if it doesn't exist)
2. Drop your MP3 in and name it exactly **`music.mp3`**
   → full path: `assets/music.mp3`

The song **starts as soon as the page opens** and **loops through every scene**.
On most phones, browsers block autoplay until the first tap — if that happens,
music starts on her **first tap anywhere** (including the Okay button). The 🔊
button in the top-right lets her mute/unmute anytime.

### 2. Preview the characters

Scenes 3, 4, and 5 use built-in SVG illustrations (guy alone, proposal, hug).
Open `index.html` on your phone and click through. If you want to swap any for
your own image later, replace the `<svg class="art"...>` block with:

```html
<img class="art" src="assets/guy.png" alt="">
```

(use `class="art-row"` for the two-person scenes)

### 3. Spotify playlist

Already wired — the last scene opens this link in Spotify:

https://open.spotify.com/playlist/6lLgx034CKPtPmy9cg28Iy

Your MP3 plays the whole time; the link is just so she can save the full playlist.

---

## Deploy for free

**Easiest — Netlify Drop (no account needed):**

1. Put `index.html`, the `assets` folder (with `music.mp3`), and this README in one folder
2. Go to **https://app.netlify.com/drop**
3. Drag the folder onto the page
4. Copy the live URL and send it to Vishalaxi 💌

**Alternative — Vercel:**

1. Sign up free at **https://vercel.com**
2. New Project → import a GitHub repo, or drag the folder if offered
3. No build settings needed — it's static HTML
4. Deploy → you get a `.vercel.app` link

Both are free forever for a site like this.

---

## Test on phone first

1. Add `assets/music.mp3`
2. Open `index.html` locally or deploy a test link
3. Click through every scene on your phone before sending the final link
