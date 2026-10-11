# Portfolio documentation

This repository is also home to my personal portfolio: **plain HTML, CSS, JavaScript, and a bundled Three.js runtime**. The complete active homepage lives in [`index.html`](https://github.com/celestial-sora/celestial-sora/blob/main/index.html).

## Run locally & deployment notes

From the repository root, run:

```sh
python3 -m http.server 4321 --bind 127.0.0.1
```

Open [http://127.0.0.1:4321](http://127.0.0.1:4321). No package installation or build step is needed.

The `main` branch deploys automatically to [celestial-sora.vercel.app](https://celestial-sora.vercel.app). [`vercel.json`](https://github.com/celestial-sora/celestial-sora/blob/main/vercel.json) serves the root as a static site. The former `/sora-preview/sora.html` URL redirects to the homepage.

The complete previous project is preserved in [archive/pre-html-cleanup-2026-10-08](https://github.com/celestial-sora/celestial-sora/tree/archive/pre-html-cleanup-2026-10-08).


## Credits & licenses

The scene and chapter layout adapt [Meng To’s ThreeUI Kage page](https://github.com/MengTo/threeui) under the MIT license in [`LICENSE`](https://github.com/celestial-sora/celestial-sora/blob/main/LICENSE). The bundled Three.js file retains its upstream license notice. Font notices are kept beside their corresponding files in [`fonts/`](https://github.com/celestial-sora/celestial-sora/tree/main/fonts); the embedded font stylesheet is preserved unchanged.

The Sekaira artwork above is an existing asset from this repository’s [`sora-art/`](https://github.com/celestial-sora/celestial-sora/tree/main/sora-art) collection. The pastel header is a self-contained SVG in [`assets/profile-header.svg`](https://github.com/celestial-sora/celestial-sora/blob/main/assets/profile-header.svg).
