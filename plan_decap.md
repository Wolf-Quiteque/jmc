# Decap CMS Integration Plan

## Integration Approach
This plan outlines the steps to integrate Decap CMS into the existing static HTML website. The approach involves:
1. Creating Markdown content files for each page
2. Setting up Decap CMS admin interface
3. Replacing hardcoded content with dynamic content loaded from Markdown
4. Using JavaScript to inject content into pages

## Pages Decapified
- [x] Decapify `carrying.html` 
- [x] Decapify `carryingplus.html`
- [x] Decapify `expo.html`
- [x] Decapify `index.html`

## Implementation Notes
- Will create content structure in `content/pages/`
- Each HTML file will have corresponding Markdown file
- Using GitHub as backend for Decap CMS
- Need to add marked.js for client-side Markdown rendering
- Will preserve existing HTML structure and styling

## Progress Tracking
- [x] Initial plan created
- [x] Admin interface setup
- [x] First page converted
- [x] `carrying.html` converted
- [x] `expo.html` converted
- [x] All planned pages converted for now.

## Configuration Notes
- Basic Decap CMS admin interface created
- GitHub backend configured
- Pages collection setup for content management
- Media folder set to /img
- First page (index.html) converted to Markdown
- `index.html` updated to load content dynamically from `content/pages/index.md` using `marked.js`.
