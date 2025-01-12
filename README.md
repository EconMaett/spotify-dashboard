# Spotify Dashboard

This repository contains the code for a Quarto dashboard that displays Spotify's [Today's Top Songs](https://open.spotify.com/playlist/5iwkYfnHAGMEFLiHFFGnP4) playlist. 

It is inspired by [Melissa Van Bussel](https://www.melissavanbussel.com/)'s submission to the Posit PBC's Table Contest.

I have adapted the original dashboard considerably since [some of the Spotify API endpoints are no longer supported](https://developer.spotify.com/blog/2024-11-27-changes-to-the-web-api).

Furthermore, I explicitly tell GitHub Actions to install R, and to install all packages using `{renv}` from the [Posit package manager](https://packagemanager.posit.co).

You can visit the live dashboard [here](https://econmaett.github.io/spotify-dashboard/dashboard.html).