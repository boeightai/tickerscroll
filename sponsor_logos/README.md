# Sponsor Logos Folder

This folder contains logo images for sponsors that will be displayed in the sponsor call widget.

## How to Add Sponsor Logos

1. **File Format**: Use PNG, JPG, or SVG files
2. **Size**: Recommended 20x20 pixels (the widget will scale them automatically)
3. **Naming**: Use descriptive names like `company_name_logo.png`

## Current Files

- `placeholder.svg` - Default placeholder logo used when no sponsor logo is available

## How to Update the Widget

To use a specific sponsor logo in the widget:

1. Add your logo file to this folder
2. Update the corresponding `<img src="sponsor_logos/your_logo.png">` in the HTML file
3. Replace `your_logo.png` with your actual filename

## Example

```html
<div class="sponsor-logo">
    <img src="sponsor_logos/example_company_logo.png" alt="Example Company Logo">
</div>
```

## Logo Guidelines

- Keep logos simple and recognizable at small sizes
- Use transparent backgrounds when possible
- Ensure good contrast against the dark widget background
- Test how the logo looks at 20x20 pixels 