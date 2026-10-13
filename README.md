# Gobble Getaway

A browser-based November training escape room. Choose one of two standalone fictional Progressive employee service-desk cases: a Florida ID card request or a Delaware non-payment reinstatement. Each case has independent steps and saved progress.

Both cases use simulated Outlook or Teams identity checks. The Delaware case follows the supplied Services guidance for the 60/61-day inception threshold, the 30/31-day payment gap, full and partial payment, draft status, event direction, and reinstatement with a lapse. Employee details, policy dates, lookups, and all actions are fictional. The game does not connect to Progressive systems and must not be used to process real requests.

## Play locally

Open `index.html` in a browser to choose a case. Delaware also has its own page at `delaware-reinstate.html`. No dependencies or build step are needed. Progress and the countdown are saved in that browser on that device.

## Publish with GitHub Pages

This repository includes a GitHub Actions workflow in `.github/workflows/pages.yml`. After the game files are pushed to `main`:

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **GitHub Actions** as the source.
3. Open the **Actions** tab and wait for **Deploy Gobble Getaway** to finish.

The game will then be available at `https://maribelrmz94.github.io/great-gobble-getaway/`. Each player keeps their own progress in their browser; a shared leaderboard would need a small server or hosted database.