# timesheet

A two-week timesheet page, live at **https://findts.github.io/timesheet/**

Open it in Safari and use Share → Add to Home Screen to keep it one tap away.
Entries are saved in the browser on the phone that typed them; nothing is sent
anywhere until the Send button is tapped, and no data is stored in this repo.

## Publishing a change

`index.html` is the whole site — one self-contained file, no build step.

    git pull                          # get any change made elsewhere first
    # edit index.html
    git commit -am "what changed"
    git push

GitHub Pages redeploys from `main` in about a minute. The URL never changes,
so a home-screen shortcut keeps working across updates.
