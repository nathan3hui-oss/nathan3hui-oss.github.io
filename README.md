# nathan3hui-oss.github.io

Web pages for 猫猫闯祸 · Paw & Crash:

- `/l/#<level code>`: a level shared from the game. With the app installed, iOS opens it straight
  in the app (universal link, see `.well-known/apple-app-site-association`); otherwise the page
  offers to open it (`pawcrash://play?c=…`) or to get the app. The code stays after the `#`, so
  nothing is sent to a server.
- `/`: a small home page.
