# Loadstone site

Public pages for [Loadstone for Windows](https://github.com/mortenbrudvik/loadstone-win) — the help
page the app's tray menu links to, and the privacy policy its Microsoft Store listing requires.

| Page | URL |
| --- | --- |
| Home | https://mortenbrudvik.github.io/loadstone-site/ |
| Help | https://mortenbrudvik.github.io/loadstone-site/help/ |
| Privacy policy | https://mortenbrudvik.github.io/loadstone-site/privacy/ |

The help URL is compiled into the app (`TrayController.HelpUrl`) and the privacy URL is filed with
the Store listing, so **neither path should change** without updating those.

Plain static HTML, no build step.
