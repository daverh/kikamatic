# Kikamatic website

The public website for Kikamatic games, served by GitHub Pages.

| Page | Address |
|---|---|
| Home | https://kikamatic.com/ |
| Crystal Quest | https://kikamatic.com/crystal-quest/ |
| Privacy policy (all games) | https://kikamatic.com/privacy-policy.html |
| Enologica privacy policy | https://kikamatic.com/enologica/privacy-policy.html |

Plain HTML and CSS, no build step. Edit a file, push to `main`, and GitHub Pages updates in a minute or two.

`privacy-policy.html` covers every Kikamatic game, with a section per game under "Our games". When a game is added or changes what it collects (ads, internet, permissions), update its section **before** that version is released, and change the effective date.

Enologica (the wine cellar app, for adults) has its own policy at `enologica/privacy-policy.html`, because the games' policy promises that nothing is collected and that the games are made for children. Its source of truth is `store/policies/privacy-policy.md` in the enologica repo; update both together, before a release that changes what the app sends.

`privacy-policy.htm` and `crystal-quest/privacy-policy.html` just redirect to it.

The Fredoka font is under the SIL Open Font License (`fonts/OFL.txt`).
