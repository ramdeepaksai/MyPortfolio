# Image Placeholder Guide

This folder is designed to hold your portfolio images. Replace the CSS placeholders with actual images to complete your portfolio.

## Recommended Images

### 1. Profile Photo (`profile.jpg`)
- **Size**: 400x400px (square format)
- **Format**: JPG or PNG
- **Usage**: Hero section and about section
- **Tips**: Professional headshot with good lighting

### 2. About Image (`about.jpg`)
- **Size**: 500x400px
- **Format**: JPG or PNG
- **Usage**: About section
- **Tips**: Could be a workspace photo, coding setup, or another professional photo

### 3. Project Screenshots
- **Size**: 600x400px (3:2 ratio)
- **Format**: JPG, PNG, or WebP
- **Naming**: `project-1.jpg`, `project-2.jpg`, etc.
- **Usage**: Projects section
- **Tips**: Show your actual project interfaces

### 4. Portfolio Preview (`portfolio-preview.png`)
- **Size**: 1200x630px
- **Format**: PNG
- **Usage**: README.md and social sharing
- **Tips**: Screenshot of your complete portfolio homepage

## How to Replace Placeholders

1. **Add your images** to this folder
2. **Update HTML** - Replace the placeholder divs with img tags:
   ```html
   <!-- Replace this: -->
   <div class="image-placeholder">
       <i class="fas fa-user"></i>
       <p>Your Photo Here</p>
   </div>
   
   <!-- With this: -->
   <img src="images/profile.jpg" alt="Your Name" class="profile-image">
   ```

3. **Update CSS** - Add styles for your images:
   ```css
   .profile-image {
       width: 100%;
       height: 100%;
       object-fit: cover;
       border-radius: 50%;
   }
   ```

## Image Optimization Tips

- **Compress images** using tools like TinyPNG or ImageOptim
- **Use WebP format** for better compression (with JPG fallback)
- **Responsive images** using `srcset` for different screen sizes
- **Lazy loading** - Images load as user scrolls (already implemented in JS)

## Free Image Resources

- **Unsplash** - High-quality stock photos
- **Pexels** - Free stock photos and videos
- **Pixabay** - Free images and vectors
- **Canva** - Create custom graphics and designs

Remember to only use images you have rights to use!
