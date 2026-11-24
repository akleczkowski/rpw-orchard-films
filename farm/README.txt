Orchard Spread, Six Years -- standalone copy of the web page

Upload all files to one folder on any web server and open index.html:
  index.html           the page
  overlay-replanting.mp4      film over the farm image, with replanting
  overlay-no-replanting.mp4   film over the farm image, without replanting

Keep the files together: the page finds the films by their names,
relative to itself. No server code is needed. The fonts load from Google Fonts; if that is blocked, the page falls back to system fonts.

To show only the films inside an existing page, the minimum is:
  <video src="overlay-replanting.mp4" controls muted playsinline width="1600"></video>

Simulated with the RPW-stochastic orchard model (8 m spacing, staged
collapse, flight step, UAE climate), 23 Nov 2026.

The farm image is for demonstration purposes only. It is not
georeferenced; the platform interface was cropped and patched out (24 Nov 2026).
