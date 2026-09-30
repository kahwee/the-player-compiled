# the-player-compiled

Compiled browser demo for inspecting VAST/VPAID ad tags with Video.js.

## Run

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000` and submit an ad-tag URL in the form. The page uses
bundled assets from [dist/](dist/), [vendors/](vendors/), and the tracked
`node_modules/video.js/dist/video.js`.

This checkout contains compiled artifacts, with no package manifest or build
commands. Remote ad URLs and the historical browser integrations have not been
revalidated; there is no configured automated test suite.
