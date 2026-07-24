# PAPA's Park Identity

PAPA's Park Identity is a p5.js generative identity tool for Pulross Area Play Association. The project explores how a small, volunteer-run community space could produce flexible social media graphics without needing a dedicated designer, while still keeping a recognisable visual language.

The tool generates abstract, imperfect shape compositions using a bright red, green, yellow, and blue palette drawn from the park's visual environment. Weather presets simplify the interface for non-designers, while advanced controls expose the underlying parameters for colour, stroke, shape count, point count, spread, rotation, randomness, and canvas format.

- Website: https://yze.design/papas/
- Process: https://yze.design/papas/process/
- Repository: https://github.com/yze1/papas

## Run

Serve the folder locally:

```bash
python3 -m http.server 5500
```

Open `http://127.0.0.1:5500/`.

## Contents

- `index.html` - interface layout and control panel.
- `script.js` - p5.js shape generation, presets, animation, and export logic.
- `p5setup.js` - shared p5 setup and SVG save helpers.
- `styles.css` - app layout and control styling.
- `assets/fonts/` - rounded font files used by the identity prototype.

## Notes

The app can export SVG assets and animated GIFs for use in social media mockups, posters, and wider identity experiments.
