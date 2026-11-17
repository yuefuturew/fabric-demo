# Garment Edit — interactive demos

**Live site: https://yuefuturew.github.io/fabric-demo/**

Companion interactive figures for *Learning to Initialize Simulation-Based Garment Panel Editing*. The drapes are
precomputed cloth simulations; the pages render them as a 3-D preview in the browser (no online cloth simulation).

| Demo | Link | What it shows |
|---|---|---|
| **Edit pipeline 3D** | [`/pipeline3d/`](https://yuefuturew.github.io/fabric-demo/pipeline3d/) | The full pipeline worn on the body — original → target → direct → learned init → ours — as five linked 3-D viewers that rotate together, plus the 2-D panel. |
| **Skirt fit studio** | [`/skirt3d/`](https://yuefuturew.github.io/fabric-demo/skirt3d/) | Drag the hem on a real draped skirt on the body and watch the 2-D panels update (10 cm measurement grid). |
| **Hem predictor** | [`/predictor/`](https://yuefuturew.github.io/fabric-demo/predictor/) | Drag a target hemline; the trained kernel-ridge model predicts the pattern edit live, entirely in-browser. |

Static, self-contained pages (three.js loaded from a CDN); hosted with GitHub Pages. Rotate to a 3/4 angle and
screenshot the pipeline viewer for a 3-D figure.
