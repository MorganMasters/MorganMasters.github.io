---
title: "Champion: ACM SIGBED Student Research Competition, ESWEEK 2025"
date: 2025-09-30
permalink: /posts/2025/09/sigbed-src-champion/
tags:
  - awards
  - birdseye
  - uav
---

**BirdsEye** took first place in the ACM SIGBED Student Research Competition at Embedded Systems Week 2025 in Taipei, Taiwan.

The entry presented BirdsEye, a UAV-based geospatial annotation pipeline that replaces manual image labeling with RTK-accurate ground geotagging: field experts place centimeter-level geotags on targets, an RTK-equipped UAV surveys the same field at 2–4 mm ground sampling distance, and a projective calibration maps the geotags into pixel-level annotations.

Headline numbers from the entry:

- **55,600 annotations across 12,500 images in roughly 12 hours of labor** — under one workday for two field workers.
- **300–500% higher annotation throughput** than GUI-based labeling, with **7× fewer workers**; per-worker efficiency improved **22–38×**.
- Projection accuracy validated at **2.2 mm GSD** (10 m altitude) and **4.4 mm GSD** (20 m altitude), under **10 cm** projection error in normal flight.
- The resulting burrow-detection CNN reached **83.7% recall** on farmland it had never seen. Precision was 35.1%, but most "false" positives were burrows human annotators had missed.

## The slides

<div style="position: relative; width: 100%; padding-bottom: 60%; height: 0; overflow: hidden; margin-bottom: 1em;">
  <iframe src="https://docs.google.com/presentation/d/12_5zbJ_F6wE7Bu6KI0W8MskZdz6UGrZBm8sfd4j3KCY/embed?start=false&loop=false&delayms=60000"
          style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;"
          frameborder="0" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"
          title="BirdsEye — ACM SIGBED SRC 2025 slides"></iframe>
</div>

Prefer a file? [Download the slides as PDF](/files/sigbed-src-2025-slides.pdf) or read the [extended abstract](/files/sigbed-src-2025-abstract.pdf).

The work is also written up in the preprint [*BirdsEye: Enabling Rapid Supervised Image Dataset Creation for Geospatial-AI*](/publications/), with co-authors Adam Korycki, T. Luca Altaffer, Nick Kuipers, Nick Bender, Colleen Josephson, and Steve McGuire.
