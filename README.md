# LEO / NTN Research Atlas

A Korean-language, **unofficial educational research index** for the public LEO/NTN research themes covered in the Kyung Hee University Wireless Systems Lab materials.

## Scope

- LEO satellite orbital geometry, Doppler-time curves, elevation and visibility
- Stochastic-geometry characterization of Doppler magnitude distribution and CDF/PDF
- Differential Doppler mitigation and NB-IoT resource allocation
- GNSS-resilient closed-loop TO/FO synchronization, PII controllers, integrator initialization and stability
- MATLAB learning checklist for Khan & Afshang (2020), **Fig. 2, page 5**

This is a study/reading map, **not** an official laboratory website, a claim of reproduced simulation results, or an endorsed University publication.

## Source literature

1. I. Ali et al., *Doppler Characterization for LEO Satellites*, IEEE Transactions on Communications, 1998.
2. I. Ali et al., *Doppler Applications in LEO Satellite Communication Systems*, 2002.
3. T. A. Khan and M. Afshang, *A Stochastic Geometry Approach to Doppler Characterization in a LEO Satellite Network*, 2020.
4. O. Kodheli et al., *Resource Allocation Approach for Differential Doppler Reduction in NB-IoT over LEO Satellite*, 2018.
5. J. Hwang et al., *Analytical Modeling and Integrator Initialization for Closed-Loop Synchronization in LEO Non-Terrestrial Networks*, IEEE TVT, 2026. DOI: [10.1109/TVT.2026.3742947](https://doi.org/10.1109/TVT.2026.3742947).
6. H. Jung, *GNSS-Resilient Synchronization for LEO Non-Terrestrial Networks*, seminar slides.

**Copyright and privacy:** Original PDFs/slides and licensed figures are **not** distributed here. The graphics are original conceptual schematics; the CDF sketch is not a numeric reproduction of Fig. 2. No private email, unpublished code, student personal information or proprietary lab files are included. Reference descriptions are educational summaries only. External literature is clearly labelled as prior work.

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server 8000` and visit `http://localhost:8000`.

## Quality check

`npm test` (Node 22 or later)

## GitHub Pages

The workflow `.github/workflows/pages.yml` deploys this static site on pushes to `main` when Pages is configured for **GitHub Actions**. In repository **Settings → Pages → Build and deployment → Source**, select **GitHub Actions**. Existing repositories and their code need no changes.