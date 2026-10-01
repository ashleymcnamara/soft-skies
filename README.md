# Soft Skies

A little sky to squeeze, stretch, and watch drift back into place.

An interactive 3D weather playground built with native WebGPU and WGSL. Everything lives in one self-contained HTML file, including the sounds. No build step or API key is needed.

## Run it

Open `index.html` in a current browser with WebGPU support, such as Chrome or Edge. You can also serve the folder locally:

```sh
python3 -m http.server 8000
```

Then visit [localhost:8000](http://localhost:8000). If WebGPU is unavailable, the app explains what is needed rather than substituting a different renderer.

## Make a little weather

- Grab the cloud with a mouse, touch, or pen. Stretch it, squeeze it, and let go.
- Explore Rain, Thunder, Snow, Sunny, Clear, Breezy, Mist, and Prismatic mist.
- Use **Squeeze** for a preview, or tab to the cloud and use Space and the arrow keys.
- Turn sound on when you want it. Pause and reset are always available.

The interface adapts to smaller screens and respects reduced-motion preferences. Your selected sky and sound preference are remembered locally; restored sound waits for an interaction before playing.

Optional real-world weather estimates are provided by [Open-Meteo](https://open-meteo.com/).
