# Video Navbar + Hero Update

This project now contains the navbar and hero section styled to match the supplied reference video.

## Files changed

- `index.html`
  - One event/location pill, matching the video.
  - Form fields changed to placeholder-style inputs like the video.
  - Submit button split into the white arrow box and purple label area.
  - `css/video-navbar-hero.css` is loaded after the existing stylesheet.

- `css/video-navbar-hero.css`
  - Final navbar and hero overrides.
  - Three independent vertical photo scrolling columns.
  - Hover on the photo collage pauses motion.
  - Responsive desktop/tablet/mobile rules.
  - `prefers-reduced-motion` support.

## Hero photos: which image to replace

All six video-matched photos are in this folder:

`assets/images/`

| Current file | Used in the layout |
| --- | --- |
| `hero-photo-1.png` | left column, tall image |
| `hero-photo-4.png` | left column, short image |
| `hero-photo-2.png` | middle column, tall image |
| `hero-photo-5.png` | middle column, short image |
| `hero-photo-3.png` | right column, tall image |
| `hero-photo-6.png` | right column, short image |

To exchange any photo, overwrite the file while keeping the **same file name**, e.g. replace:

`assets/images/hero-photo-1.png`

with your new photo renamed as:

`hero-photo-1.png`

Do not change the image name or the hero code will not need any edit.

## PSE ZIP note

The attached `Premier Schools Exhibition (PSE) LP (12-06-2025).zip` contains only two assets:

- `Isolation_Mode.png`
- `Isolation_Mode-1.png`

They are the decorative laurel images, not the six hero photos. The hero photos already exist in this C_Project2 source folder.

## Run project

Open `index.html` directly, or use VS Code **Live Server** for the best result.

## Latest header adjustment
- Header is fixed to the Figma reference height: **100px** on desktop (78px mobile).
- After scroll, the navbar uses the navy-to-purple gradient reference color.
- The Register Now button now uses the white hover state and retains keyboard focus styling.
