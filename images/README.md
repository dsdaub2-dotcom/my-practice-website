# Images Directory

Place your images in this directory.

## Required Images:

### 1. Logo
- **Filename**: `logo-placeholder.svg` or `logo.svg`
- **Recommended size**: 200×200px
- **Format**: SVG preferred (or PNG with transparency)
- **Usage**: Appears in header on all pages

### 2. Provider Headshots
- **Filenames**: `placeholder-profile.jpg` or individual names (e.g., `dr-jane-doe.jpg`)
- **Recommended size**: 500×500px minimum
- **Format**: JPG or PNG
- **Usage**: Specialist cards and profile pages
- **Tips**: 
  - Use professional headshots
  - Consistent lighting and background
  - Square aspect ratio
  - Warm, approachable expressions

### 3. Hero Background (Optional)
- **Filename**: `hero-bg.jpg`
- **Recommended size**: 1920×1080px
- **Format**: JPG
- **Usage**: Homepage hero section
- **Tips**:
  - Use calming nature images (trees, water, sunrise)
  - Avoid busy patterns
  - Ensure good contrast with text overlay

## Image Optimization Tips:

1. **Compress images** before uploading
   - Use tools like TinyPNG or ImageOptim
   - Target: <200KB per image for web

2. **Provide alt text** in HTML
   ```html
   <img src="images/dr-jane-doe.jpg" alt="Dr. Jane Doe, Psychiatrist">
   ```

3. **Use appropriate formats**
   - SVG for logos and icons
   - JPG for photos
   - PNG for images needing transparency

4. **Consider WebP format** for better compression (modern browsers)

## Quick Start:

1. Replace `logo-placeholder.svg` with your actual logo
2. Replace `placeholder-profile.jpg` with provider photos
3. Update image references in HTML files to match your filenames
4. Add alt text for accessibility

## Placeholder Files:

Until you have real images, you can:
- Keep the placeholder filenames referenced in the HTML
- Use temporary images from placeholder services like:
  - https://placehold.co/500x500
  - https://via.placeholder.com/500

Example temporary usage:
```html
<img src="https://placehold.co/500x500/6B9AC4/FFFFFF?text=Provider+Photo" alt="Provider Name">
```

Remember to replace these with real, professional images before launch!
