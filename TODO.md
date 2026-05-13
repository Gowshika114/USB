# TODO - Gallery cursor tooltip captions

## Goal
When user hovers over award/gallery pictures, show a professional tooltip sentence describing what the photo is.

## Plan
1. Inspect existing gallery HTML/CSS to find where hover happens and what markup is missing.
2. Update `index.html` gallery items to include a `data-caption` attribute for each image.
3. Add a tooltip element overlay in each `.gallery-item` (using CSS `::after`/`content: attr(...)` or by adding a child span).
4. Add CSS in `style.css` for tooltip style, position, animation, and mobile fallback.
5. Verify it works for both Awards and Best Performers sections.

