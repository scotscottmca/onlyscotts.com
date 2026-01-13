# GitHub Copilot Instructions

## Project Overview
This is a single-page website hosted on GitHub Pages that displays a repeating tiled pattern of an image.

## Structure
- **index.html** - The main and only HTML file
- **IMG/scott.jpeg** - The image file that is displayed

## Design Requirements
- The image `IMG/scott.jpeg` should be displayed in an infinite grid pattern, both horizontally and vertically
- 10px gap between each row and column of images
- No header, no footer, no navigation - just the tiled image pattern
- The grid should fill the entire viewport and extend beyond for scrolling
- Minimalist approach: no additional UI elements

## Technical Implementation
- Uses CSS Grid for layout
- JavaScript dynamically generates enough image tiles to fill the viewport
- Responsive: adjusts the number of tiles on window resize
- Images are displayed as background images in div elements for performance

## When Making Changes
- Maintain the minimalist design - do not add headers, footers, or navigation
- Keep the 10px gap requirement between tiles
- Ensure the image path `IMG/scott.jpeg` remains correct
- Preserve the infinite scrolling pattern behavior
- Any styling changes should not introduce additional elements to the page
