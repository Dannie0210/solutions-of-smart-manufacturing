# Solutions of Smart Manufacturing

An English-language client proposal for glass-jar lid inspection. The public site is a single static HTML file (`index.html`), suitable for GitHub Pages.

## Content

1. **Project Scenario:** system architects presenting a technical feasibility study to a demanding food-packaging customer.
2. **Current Challenges:** food safety, reliable rejection, jar stabilization, and customer metal lid diameters of **27–110 mm**.
3. **Our Solutions:** keyboard-accessible tabs:
   - **Plan A:** automated non-contact laser triangulation and pneumatic rejection.
   - **Plan B:** manual operator lid-press inspection with BOO indication, side rejection, and variable labor cost.

## Demo integration

The animated demos are **embedded live** from the user's existing GitHub Pages projects:

- https://dannie0210.github.io/laser-lid-inspection/
- https://dannie0210.github.io/labor-intelligent/

This avoids duplicating the complex animations in a new codebase; improvements to the original animations are reflected here automatically. Because these are hosted separately, internet access and availability of the two original GitHub Pages sites are necessary. Each plan provides an **Open original** link for mobile/full-screen access if embedding is blocked by a browser.

## GitHub Pages deployment

1. Create a **public** repository `solutions-of-smart-manufacturing`.
2. Upload `index.html` to the repository root on the `main` branch.
3. Open **Settings → Pages**, select **Deploy from a branch**, `main`, and `/(root)`; Save.
4. Site URL: https://dannie0210.github.io/solutions-of-smart-manufacturing/

## Status of specifications

This is a conceptual feasibility proposal, not verified production performance. The customer requirement is **27–110 mm**; the current Plan A demonstration lists **25–110 mm** as its preliminary engineering reference. Reference manufacturer or workshop figures (e.g., laser measurement precision and throughput) have not been independently validated. The Plan B labor-cost model uses €400/operator/month, 32 h/week, a 12-month horizon and a €110,000 planning budget, but excludes other labor and equipment costs.