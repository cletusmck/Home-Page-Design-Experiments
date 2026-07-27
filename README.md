# Bridge — Home Page Design Experiments

Creative concepts for the new Bridge homepage. The viewer at `index.html` lets you flip through every concept (V1, V2, V3, ...) with left/right arrows that stay on top of the designs. Keyboard arrow keys work too, and `#v3` in the URL deep-links to a specific version.

## Viewing

Once GitHub Pages is enabled for this repo (Settings → Pages → deploy from `main`, root), the viewer is served at the repo's Pages URL. Locally, run any static server from the repo root:

```bash
python3 -m http.server 8080
```

and open http://localhost:8080/.

## Adding your concept

1. Add a single self-contained HTML file to `concepts/` (inline your CSS/JS).
2. Reference shared images with relative paths, e.g. `../assets/stories/...`. Add new imagery under `assets/`.
3. Append one entry to `concepts.js`:

```js
{ file: "concepts/v7-your-name.html", title: "Your Concept", author: "You" }
```

Your concept becomes the next V number automatically. Please keep copy within the Bridge messaging guardrails: state Bridge's role accurately (Bridge Direct Lending vs. Financing Secured by Bridge), use only approved proof facts, no marketplace language, and add "subject to underwriting" wherever funding is implied.

## Current concepts

| Version | Title | Idea |
| --- | --- | --- |
| V1 | Funded Object | Rotating funded closings as the homepage centerpiece |
| V2 | Milestone | LoveFrom-style white type composition: Bridge, arrives first; path choices follow; then successes per track |
