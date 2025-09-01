# VB WebGPU Torus Model - JWST Early Galaxies Overlay

<h2>Description</h2>
<p>This interactive simulation instantiates nested toroidal resonance layers and overlays the positions of JWST early galaxies. It illustrates how the VB framework situates cosmological structure formation within a scalable toroidal lattice.</p>

<h2>User Interface and Controls</h2>
<p>UI sliders expose R/r, tilt, child shift, smooth-union k, exposure, and recursion depth; toggles switch Sphere projection, Hologram mode (interior/throat view), JWST overlay, and energy field. HUD shows GPU + FPS; controls: WASD/mouse, Q/E (down/up), Shift (faster), O (auto-orbit), plus a simple audio heartbeat. 

<h2>Mock early-galaxy tracers</h2>
<p>The overlay uses mock points—synthetic RA/Dec/redshift samples drawn to resemble early JWST number counts and z-distribution over the JADES-GS footprint.</p> <p>A few named JADES candidates may be included as anchors and flagged is_real=true; all other points are Monte-Carlo draws (no photometry/morphology). Purpose: visualization and stress-testing of the VB toroidal mapping, not inference.</p>



| ID                         | RA (deg) | Dec (deg) |     z |
| -------------------------- | -------: | --------: | ----: |
| JADES-GS-53.13918-27.78273 | 53.13918 | -27.78273 | 10.49 |
| JADES-GS-53.15883-27.77350 | 53.15883 | -27.77350 | 10.84 |
| JADES-GS-53.16863-27.79276 | 53.16863 | -27.79276 | 11.71 |
| JADES-GS-53.09731-27.84714 | 53.09731 | -27.84714 | 11.53 |
| JADES-GS-53.02618-27.88716 | 53.02618 | -27.88716 | 11.56 |
| JADES-GS-53.04017-27.87603 | 53.04017 | -27.87603 | 12.10 |
| JADES-GS-53.16476-27.77463 | 53.16476 | -27.77463 | 12.31 |
| JADES-GS-53.03547-27.90037 | 53.03547 | -27.90037 | 12.38 |
| JADES-GS-53.16635-27.82156 | 53.16635 | -27.82156 | 12.46 |
| JADES-GS-53.06475-27.89024 | 53.06475 | -27.89024 | 12.93 |
| JADES-GS-53.14988-27.77650 | 53.14988 | -27.77650 | 13.41 |
| JADES-GS-53.14673-27.77901 | 53.14673 | -27.77901 | 13.68 |
| JADES-GS-53.02868-27.89301 | 53.02868 | -27.89301 | 13.52 |
| JADES-GS-53.07557-27.87268 | 53.07557 | -27.87268 | 14.38 |
| JADES-GS-53.08294-27.85563 | 53.08294 | -27.85563 | 14.39 |
| JADES-GS-53.10762-27.86013 | 53.10762 | -27.86013 | 14.63 |
| JADES-GS-53.02212-27.85724 | 53.02212 | -27.85724 | 14.59 |
| JADES-GS-53.07427-27.88592 | 53.07427 | -27.88592 | 14.36 |
| JADES-GS-53.11127-27.89780 | 53.11127 | -27.89780 | 14.22 |


<h2>Run Instructions</h2>
<p>Run locally in Chrome/Edge 113+ with WebGPU; no server required</p>

