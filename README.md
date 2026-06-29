# Newcastle Metro Life Expectancy Microsite

This repository contains a static Vercel-ready microsite for a public blog post
about Newcastle, deprivation and life expectancy around the Tyne and Wear Metro.

## Contents

- `index.html` - the public story page with the embedded Metro animation.
- `technical-note/index.html` - data sources, calculation notes and limitations.
- `assets/metro_life_expectancy_male_female_comparison_animation.mp4` - the embedded animation.

The base Metro map used in the animation was sourced from Travel North East:
https://travelnortheast.uk/ways-to-travel/metro/metro-maps/

The faded hero background map is `assets/newcastle-osm-hero-map.png`, sourced
from Wikimedia Commons:
https://commons.wikimedia.org/wiki/File:Newcastle_upon_Tyne_OSM_02.png

## Deployment

The site is plain static HTML/CSS and can be deployed directly on Vercel from the
repository root. No build step is required.

The public page intentionally does not offer download links for the video or the
working dataset.

## Core message

The site frames the work as a human story: Andrew Kingston was born in a D1
area, ranked 478 out of 33,755 English LSOAs, and uses the Metro map to explore
how life expectancy inequality is visible across familiar local geography.

The current estimates are area-based 2019 to 2023 life expectancy estimates.
They are not individual predictions, but they show structural differences in the
conditions connected to health and length of life.
