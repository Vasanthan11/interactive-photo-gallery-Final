# Interactive Photo Gallery

Final version for the accessible Interactive Photo Gallery assignment.

## Files

- `index.html` - gallery HTML and event listeners
- `css/gallery.css` - gallery styling
- `js/gallery.js` - mouse, keyboard, and tabindex functionality

## Required functionality

- Six images with alternative text
- Mouseover interaction
- Mouseleave interaction
- Keyboard focus interaction
- Keyboard blur interaction
- Page-load event
- Automatic `tabindex="0"` assignment using a `for` loop
- Console message to confirm the page-load function runs

## Testing checklist

1. Open `index.html` in a browser.
2. Move the mouse over each image and confirm the preview changes.
3. Move the mouse away and confirm the preview resets.
4. Press Tab repeatedly and confirm each image receives focus.
5. Confirm the preview changes when an image receives keyboard focus.
6. Open the browser developer console and confirm the `addTabIndex` message appears.
7. Validate the HTML with the W3C Markup Validation Service.
8. Check the page with WAVE.
9. Check the page with axe DevTools.
