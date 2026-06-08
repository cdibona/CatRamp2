# Cat Ramp Cut Sheet Generator

**▶ Live tool: https://cdibona.github.io/CatRamp2/**

A single-file web app that produces a printable **cut sheet, lumber takeoff, a 3D view, and shop diagrams** for a folding, window-sill cat ramp with side "wings" — built to keep a recovering cat from jumping off the sides and overextending.

Everything is adjustable: sill width/height, ramp length, wing reach, traction cleats, folding-leg geometry, and the sill hook. All inputs are encoded in the URL, so a copied link reproduces your exact design.

## Use it

Just open `index.html` in any browser — no build, no dependencies, works offline.

## Publish on GitHub Pages

1. Create a repo and push these files (`index.html`, `README.md`).
2. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Pick `main` / `(root)` and save.
4. Your tool is live at `https://<you>.github.io/<repo>/` in a minute or two.

## The design (defaults match the original ask)

- **Sill:** 34″ wide, 23″ off the ground
- **Ramp:** 50″ along the slope (≈27° — gentle), ¾″ plywood
- **Wings (optional):** flat triangular panels (not upright walls). Each one hangs on the ramp's side edge with **removable-pin (loose-pin) hinges** and fans down to the floor — **flush against the window wall** (no gap) and **flush to the floor** (no lip). Widest at the sill, tapering to nothing at the base. A bigger *wing reach* makes the surface gentler at the cost of a wider footprint. Untick "Include side wings" to drop them entirely.
- **Support (pick one):** **folding wall posts + 2 cross beams** (default — hinged to the ramp top, fold back flat, no runners), **wall posts + floor runners**, or a folding **A-frame** (two leg pairs that link at a center pin). The two posts are hinged to the ramp top and locked together by **2 cross beams**; the cut list gives the **post-top hinge angle**, the **ramp-to-floor angle**, and the **post spacing**.
- **Carpet & tape:** computes coverage for the deck + both wings, the running length from a roll width you set, plus double-sided carpet-tape footage.
- **Sill hook:** a top cleat that drops over the sill edge so the ramp can't slide

The cut list includes the **wing corner angles** (they sum to 180°) so you can lay the triangle out by angle as well as by edge length.

The geometry is an honest first cut — measure your actual sill before cutting.

## License

[MIT](LICENSE) © 2026 Chris DiBona.
