# Snap Read

A snap-by-snap NFL tracker for iPad. Log what you see before and after every snap, watch tendencies build up live, and get a halftime scouting report on both teams' offense and defense.

## Put it on GitHub Pages

1. Unzip `snap-read.zip` in the Files app (tap it).
2. In Safari on github.com, create a new repository (for example `snap-read`).
3. In the repository: **Add file → Upload files**, select every file from the unzipped folder, and commit.
4. **Settings → Pages**: deploy from the `main` branch, root folder, and save.
5. After a minute or two the app is live at `https://YOUR-NAME.github.io/snap-read/`.

## Add it to the home screen

Open the Pages address in Safari, then **Share → Add to Home Screen**. Always open the app from that icon.

## Your data

- Everything stays on the iPad. Home-screen web apps keep their own storage, separate from Safari tabs, so games logged in the home-screen app won't appear in a Safari tab (and the other way round).
- Back up after each game: **Season → Back up now → Save to Files**. **Restore from file** merges a backup back in.
- **Export plays (CSV)** gives you every snap in a spreadsheet.

## Updating

Upload the new `index.html` (and `sw.js`) over the old ones. The app checks the network first, so the next launch while online picks up the new version. Logged games aren't touched.

## During a game

- **Before the snap**: tap what you can see: your run/pass call, personnel, QB alignment, motion, safeties. Skip anything you missed; a blank is better than a guess.
- **After the snap**: what happened, where it went, yards, then **Log snap**. Down, distance and ball spot update on their own; tap the situation at the top to fix anything.
- **Focus**: each quarter trains one read (Q1 personnel, Q2 safeties, Q3 run blocking, Q4 pass rush). Its fields get a yellow marker and the chalkboard card tells you where to look. Change it anytime.
- **Tendency meter**: under "Your call", shows what this offense has done in the look you just tapped, this game and earlier in the season.
- **Halftime**: Game menu → End of 1st half opens the report. Later, "2nd half vs 1st" shows who adjusted.

## Credits

- Barlow Condensed font © 2017 The Barlow Project Authors, SIL Open Font License 1.1 (see `FONT-LICENSE.txt`), embedded in `index.html`.
- Success-rate definition (40% / 60% / 100% of yards to go): [Sharp Football Analysis](https://www.sharpfootballanalysis.com/nfl-stats/offense/efficiency/run-pass-success-rate-2016/).
