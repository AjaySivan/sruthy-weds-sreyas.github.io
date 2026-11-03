# Sruthy & Sreyas — wedding invitation (bride's family)

Opening: thoranam, Lord Ganesha and a gold kolam. Tapping the centre blooms the kolam, petals fall and the music starts.
Then the invitation in a temple arch, the muhurtham clock, the road from Chenasseril House to the venue, the countdown and the closing.

## Files
- `index.html` – the page
- `styles.css` – look and layout
- `script.js` – kolam, petals, clock, road and car, music, countdown
- `assets/card.jpg` – the printed card shown in View Full Card
- `audio/` – put the song here

## Adding the music
Save the song as `audio/music.mp3` (exactly that name). It starts when the guest taps the centre of the kolam.
The music button appears top right once it plays. Keep the file under about 5 MB.

## Hosting on GitHub Pages
Upload everything in this folder (not the folder itself) to a public repository, then
Settings → Pages → Deploy from a branch → `main`, `/ (root)`.

## After changing a file
Raise the number in `styles.css?v=1` / `script.js?v=1` in index.html (to v=2 and so on), so phones load the new version.
