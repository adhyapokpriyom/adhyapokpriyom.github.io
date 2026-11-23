---
layout: page
permalink: /tools-and-images/
title: "tools & images"
nav: true
nav_order: 4
_styles: >
  article h2 { font-family: 'Roboto Slab', serif; font-weight: 400; color: var(--global-theme-color); }
  .scope-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 1.25rem; margin: 1.5rem 0; }
  .scope-grid figure { margin: 0; }
  .scope-grid img { width: 100%; aspect-ratio: 1 / 1; object-fit: contain; border-radius: 6px; background: #000; }
  .scope-grid figcaption { font-size: 0.85rem; margin-top: 0.4rem; text-align: center; }
---

## Imaging

Head crowns of three cnidarians, stained for actin (phalloidin) and nuclei (DAPI) during the final module of the Embryology: Concepts and Techniques in Modern Developmental Biology course at the [Marine Biological Laboratory](https://www.mbl.edu/), Woods Hole (2022). Imaged on an LSM 780 confocal with a 10× objective. Click an image to see it full size.

<!-- To add an image: upload it to assets/microscopy/, then copy one <figure> block
     and change the file name (twice), the alt text and the caption. -->

<div class="scope-grid">
  <figure>
    <a href="/assets/microscopy/nematostella.jpeg" target="_blank"><img src="/assets/microscopy/nematostella.jpeg" alt="Nematostella head crown with tentacles radiating around the mouth, green fluorescence on black" loading="lazy"></a>
    <figcaption><em>Nematostella vectensis</em></figcaption>
  </figure>
  <figure>
    <a href="/assets/microscopy/aiptasia.jpeg" target="_blank"><img src="/assets/microscopy/aiptasia.jpeg" alt="Aiptasia head crown with many long curling tentacles, green and blue fluorescence on black" loading="lazy"></a>
    <figcaption><em>Aiptasia</em></figcaption>
  </figure>
  <figure>
    <a href="/assets/microscopy/hydra.jpeg" target="_blank"><img src="/assets/microscopy/hydra.jpeg" alt="Hydra head with five tentacles, green fluorescence on black" loading="lazy"></a>
    <figcaption><em>Hydra</em></figcaption>
  </figure>
</div>

## Code

Analysis tools for quantifying signaling and segmentation in the zebrafish notochord.

**[notochord_oscillator](https://github.com/padhyapok/notochord_oscillator)**<br>
Calculation of Erk activity from segmented cells and nuclei in Cellpose.

**[segmentation_index](https://github.com/padhyapok/segmentation_index)**<br>
Quantifying sequential order of notochord segments.

**[notochord_area_plotter](https://github.com/padhyapok/notochord_area_plotter)**<br>
Quantifying notochord segment features.
