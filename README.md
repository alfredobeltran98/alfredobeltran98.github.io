# Portfolio

Static portfolio site. No framework, no build step. Plain HTML and CSS.

## Structure

    /index.html                              English
    
    /projects/supplements-upsell.html        Upsell Opportunity Ranker
    /projects/quote-to-actual.html           Quote-to-Actual Health Check

    /es/index.html                           Spanish
    
    /es/proyectos/suplementos-upsell.html
    /es/proyectos/cotizado-vs-real.html

    /assets/                                 portrait.jpg, avatar.jpg
    /alfredo-beltran-cv.pdf

Two views of the same person: a short default landing page, and a longer
full profile. Each page hardcodes a link to its counterpart in the other
language and to the other view.

## Local preview

    python3 -m http.server 8000

Then open http://localhost:8000

Root-relative links (`/projects/...`) only resolve when served, not when
opening the file directly from Finder.

## Deploy

Pushed to GitHub, deployed by Netlify from the repo root.
