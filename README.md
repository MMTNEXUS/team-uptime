# TEAM uptime

Checks https://team.mmtnexus.com every 10 minutes from outside the server (GitHub Actions).

- The sign-in page and the registration page must load (HTTP 200 with the expected title), 3 tries each.
- If either fails, the run fails and an issue **"TEAM is down"** is opened (later failures add comments). GitHub emails you about both.
- When the site is back, the issue is closed automatically.

Run it by hand: **Actions → TEAM uptime → Run workflow**.
