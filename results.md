# Speedlify API and Lighthouse scores changelog before integrated into build scripts with netlify
Until I add Netlify build script to run `npm run test-pages` at the specified asset-cache time, this Markdown file will act as my version control. I'm using this file to rebuild tdspeedlify.netlify.app so everything is updated after a new run (until I figure out build scripts with netlify).

## Speedlify Instances - currently only for 11tygallery.netlify.app (soon to add my personal site)
1. Run #1 - September 7th 9ish PM
    * Before addition of speedlify-score web component in footer
2. Run #2 - September 8th 9:45pm
    * speedlify-score web component embedded in page footer to include lighthouse scores for each page
    * Adding this slowed down the site a little bit as I need to read up on the lighthouse documentation for avoiding "critical request chains" and reducing large contentful paint
    * Performance drops from 100 to 99 due to large contentful paint taking up to 2.0s at times
    * Hundos across the board otherwise
    * NOTE - only performance score saw change in run #2
3. Run #3 - September 9th 