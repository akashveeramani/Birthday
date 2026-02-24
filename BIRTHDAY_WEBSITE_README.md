# 🎂 Stunning Multi-Page Birthday Surprise Website

A visually breathtaking 6-page birthday surprise website with stunning animations, interactive memory cards, and photo upload capabilities. Built with pure HTML, CSS, and JavaScript.

## 📄 Pages Overview

### 1. **index.html** - The Landing Page
- **Theme:** Aurora-style gradient background with deep purple-to-black starfield
- **Features:**
  - Animated aurora gradient background
  - Twinkling stars effect
  - Floating rose petals with rotation animations
  - Centered glowing text with shimmer effect
    - "HAPPY BIRTHDAY" in Playfair Display (80px+)
    - Name in Great Vibes script font (110px+)
  - CSS heart-shaped button with pulse animation
  - Smooth fade-out transition to page2.html
  - Fully responsive design

### 2. **page2.html** - The Main Love Letter Page
- **Section 1 - Hero Block:**
  - Cinematic entrance animation
  - Typewriter effect for the heartfelt message
  - Soft bokeh blur background with slow gradient animation
  - Lora serif font (22px) with generous line height
  - Background transitions through rose → lavender → blush pink

- **Section 2 - Color Changing Scroll Animation:**
  - Dynamic background color transitions as user scrolls
  - Smooth color palette: deep navy → violet → emerald → warm amber → rose
  - Floating scroll indicator arrow with bounce animation

- **Section 3 - Memory Cards (2x2 Grid):**
  - 4 interactive memory cards (School / Apartment / Farewell / Journey)
  - 3D perspective tilt effect on mousemove
  - Glowing border animation on hover
  - Tooltip popups with poetic preview text
  - Smooth page transitions on click
  - Fully responsive grid layout

### 3. **school.html** - School Memories (Handwritten Notebook Theme)
- **Design:**
  - Ruled notebook paper background (blue horizontal lines)
  - Red vertical margin line on left (60px)
  - Caveat handwriting font for all text
  - Slightly rotated text (±1-2 degrees) for authenticity

- **Photo Section - Billboard Concept:**
  - 5 large billboard-style frames
  - Thick black borders (20px)
  - CSS metal post structure below frames
  - Weathered look with sepia + contrast filters
  - Subtle sway animation on billboards
  - Hidden file input for each billboard
  - Instant image preview with FileReader API
  - Fully responsive grid

### 4. **apartment.html** - The Apartment (Industrial/Brick Wall Theme)
- **Design:**
  - Dark brick/stone wall CSS pattern (repeating gradient)
  - Dim moody lighting (radial gradient vignette)
  - Roboto Slab bold font for headings
  - Color palette: dark grey, rust red, charcoal, muted gold

- **Photo Section - Posters on Brick Wall:**
  - Each poster has:
    - Random rotation (−3deg to 4deg)
    - Torn edge effect using clip-path
    - Beige tape strips at top corners (CSS pseudo-elements)
    - Subtle curl effect at corner
    - Drop shadow for depth
  - Clickable poster frames for file upload
  - Instant image preview
  - Responsive layout

### 5. **farewell.html** - Farewell Night (Party Theme)
- **Design:**
  - Festive venue with string lights and bokeh background
  - Multiple decorative bokeh circles (glowing, blurred)
  - Warm color palette: gold, teal, coral, white
  - Moody dark background with colorful overlays

- **Content Style - Chat Bubbles:**
  - Left bubbles (soft blue) = Her side
  - Right bubbles (warm coral) = Your side
  - Border-radius tail shapes
  - Staggered fade-in animations on page load
  - Heartfelt conversation-style text

- **Photo Section - Pamphlet Style:**
  - Colorful header banners above each frame
  - Bold titles ("UNFORGETTABLE MOMENT", etc.)
  - Decorative borders (outline + border layering)
  - Bottom strip with decorative striped pattern
  - Slight rotation for authenticity
  - File upload enabled on each pamphlet

### 6. **journey.html** - The Journey (Vintage Travel Journal Theme)
- **Design:**
  - Vintage map texture with sepia overlay
  - Soft cream/beige background with subtle patterns
  - Abril Fatface font for location names
  - Lato font for body text
  - Caveat script font for handwritten touches

- **Structure:**
  1. **Departure Terminal Block** (top)
     - Dark background with monospace white font
     - Airplane icon
     - Journey beginning statement

  2. **Vertical Timeline** (center)
     - Centered line with alternating left-right content blocks
     - 5 journey stages with styled dots
     - Torn journal page style (slightly rotated)
     - Scroll-triggered fade-in animations
     - Polaroid photo frames at each node
       - White borders (thicker at bottom)
       - Caption area in handwriting font
       - Slight rotation effect
       - File upload on click

  3. **Destination Postcard** (bottom)
     - Grand arrival section
     - Bold location name in Abril Fatface
     - Decorative postcard border (dashed + double)
     - Postage stamp CSS shape in corner
     - Multiple photo upload areas

## 🎨 Design Features

### Color Palettes Used:
- **Page 1:** Deep Purple (#1a0033), Black (#0a0a1a), Gold (#ffd700), Pink (#ff69b4)
- **Page 2:** Rose (#3d1a2d), Lavender (#2a1a4f), Navy (#1a2a4f), Emerald (#2a4f3f), Amber (#4f4f1a)
- **Page 3:** Cream (#fffaf0), Red (#ff6b6b), Blue (#4a90e2)
- **Page 4:** Dark brown (#2c2c2c), Rust red (#5a4a3f), Gold (#c4a747)
- **Page 5:** Dark (#1a1a2e), Gold (#ffb74d), Teal (#00bcd4), Coral (#ff6e40)
- **Page 6:** Cream (#f5f0e6), Gold (#b8860b), Dark brown (#6f5c3e)

### Typography:
- **Google Fonts Used:**
  - Playfair Display (serif display)
  - Great Vibes (elegant cursive)
  - Lora (elegant serif body text)
  - Caveat (handwriting style)
  - Roboto Slab (bold slab-serif)
  - Abril Fatface (display font)
  - Lato (clean sans-serif)

### Animation Features:
- ⭐ Aurora gradient animation
- 🌟 Twinkling stars
- 🌸 Floating petals with rotation
- ✨ Text glow shimmer effect
- 💓 Heart pulse animation
- ⌨️ Typewriter effect (letter-by-letter)
- 📊 Color-changing scroll animation
- 🎯 3D perspective tilt on cards
- 🎬 Fade-in/fade-out transitions
- 📜 Scroll-triggered animations
- 🎪 Sway animations on billboards
- 💬 Staggered message animations

## 🖼️ Photo Upload Feature

All pages with photo sections use the same pattern:
```javascript
- Hidden <input type="file" accept="image/*">
- Click on frame to open file picker
- FileReader API for instant preview
- No server required (local preview only)
- Responsive image sizing
- Maintains aspect ratios
```

## 📱 Responsive Design

- **Desktop:** Full-featured experience with all animations
- **Tablet:** Optimized grid layouts and font sizes
- **Mobile:** Single-column layouts, adjusted font sizes
- **Touch-friendly:** Larger click targets for buttons
- Media queries for screens < 768px

## ✨ Technical Highlights

✅ **Pure HTML/CSS/JavaScript** - No frameworks or libraries
✅ **Smooth Page Transitions** - CSS fade-out animations
✅ **IntersectionObserver** - For scroll-triggered effects
✅ **CSS Animations** - Keyframes for all motion
✅ **CSS Grid & Flexbox** - Responsive layouts
✅ **CSS Pseudo-elements** - For decorative effects (::before, ::after)
✅ **JavaScript Events** - mousemove, scroll, click handlers
✅ **FileReader API** - Local image preview
✅ **Backdrop-filter** - Blur effects on buttons
✅ **Transform Properties** - 3D rotations and tilts
✅ **Clip-path** - Complex shapes and torn edges
✅ **Radial/Linear Gradients** - Complex backgrounds

## 🚀 How to Use

1. **Open index.html** in a web browser
2. **Click the heart button** to navigate to page 2
3. **Scroll down** to see the color-changing background
4. **Hover over memory cards** to see 3D tilt and tooltips
5. **Click any memory card** to explore that theme
6. **Click any photo frame** to upload an image from your device
7. **Use back button** on each page to return

## 📝 Customization

You can customize:
- Name display: Click on the name on index.html to enter a custom name
- Love letter text: Edit the text in the `text` variable on page2.html
- Messages: Edit the message bubbles in farewell.html
- Timeline content: Edit the timeline items in journey.html
- Colors: Modify CSS color variables throughout

## 🎯 Features Checklist

✅ 6 complete HTML pages
✅ Aurora/starfield animated background
✅ Glowing text with shimmer animation
✅ Pure CSS heart button
✅ Typewriter effect
✅ Color-changing scroll animation
✅ 3D perspective tilt cards
✅ Tooltip popups
✅ Handwritten notebook theme
✅ Billboard photo frames
✅ Sway animations
✅ Brick wall theme
✅ Torn edge posters
✅ Tape strips (CSS)
✅ Curled corner effects
✅ Party venue theme
✅ Chat bubbles (left/right)
✅ Pamphlet-style frames
✅ Travel journal theme
✅ Timeline with polaroids
✅ Postcard design
✅ File upload on all photo frames
✅ Instant image preview (FileReader API)
✅ Smooth page transitions
✅ Fully responsive design
✅ Back buttons on all pages
✅ All Google Fonts implemented
✅ No external libraries or frameworks
✅ Clean, commented code

## 🎊 Perfect For

🎂 Birthday Celebrations
💑 Anniversary Surprises
💝 Proposal Ideas
🎁 Special Occasions
📸 Memory Collections
💌 Love Confessions

---

**Created with ❤️ for someone special**

Enjoy your stunning birthday surprise website!
