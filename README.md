# Roster Shuffle

Randomly assign people to dates. No one repeats within a date column, and each person's turns stay a minimum number of days apart. Results only change when you click Shuffle.

## Use it

1. Paste names into **People**, one per line.
2. Set the minimum number of days between a person's turns.
3. Paste dates into **Date 1**, one per line (`10/5/2026` or `2026-10-05`). Click **+ Add date column** for more.
4. Click **Shuffle**.
5. Click **Copy for Sheets**, then paste into cell A1 of a spreadsheet.

The **By person** panel shows each person's dates so you can check the spacing.

## Rules

- A name is never used twice in the same date column.
- A person can appear in more than one column, but their turns are always at least the set number of days apart.
- If no arrangement fits, the app says so. Lower the gap or add more names.
- Each date column needs at least as many names as dates.

## Run it

It's a single `index.html` file with no build step and no server. Open it in a browser, or host it with GitHub Pages:

1. Go to **Settings → Pages**.
2. Set the source to the main branch, root folder.

## Privacy

Everything runs in the browser. Names and dates are saved only in the visitor's own browser (localStorage) and are never sent anywhere.
