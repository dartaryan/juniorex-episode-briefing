# JUNIOREX - Episode Briefing: AI and UI/UX Design

A briefing page for podcast hosts of JUNIOREX - a podcast episode about AI and UI/UX design for juniors.

## Project Structure

```
juniorex-episode-briefing/
├── index.html          # Main page
├── README.md           # This file
├── IMAGE_PROMPTS.md    # Prompts for generating images with AI
└── images/
    ├── logo.png        # Main logo (transparent background)
    └── logo-white.png  # White logo for footer (transparent background)
```

## Quick Setup

### 1. Create Repository

```bash
# Create a new repo on GitHub named juniorex-episode-briefing
# Or any other name you prefer

git clone https://github.com/YOUR_USERNAME/juniorex-episode-briefing.git
cd juniorex-episode-briefing
```

### 2. Copy Files

Copy the following files to your repo:
- `index.html`
- `README.md`
- `IMAGE_PROMPTS.md`

### 3. Add Images

Create an `images/` folder and add the logos:

```bash
mkdir images
# Copy logo.png and logo-white.png to the folder
```

If you don't have logos ready, see `IMAGE_PROMPTS.md` for AI image generation prompts.

### 4. Push to GitHub

```bash
git add .
git commit -m "Initial commit - episode briefing page"
git push origin main
```

### 5. Enable GitHub Pages

1. Go to your repo's **Settings** on GitHub
2. Scroll down to **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select **main** and folder **/ (root)**
5. Click **Save**

Within a few minutes, the site will be available at:
```
https://YOUR_USERNAME.github.io/juniorex-episode-briefing/
```

## Customization

### Changing Colors

Colors are defined at the top of the CSS in `index.html`:

```css
:root {
    --orange-main: #F47B20;    /* Main orange */
    --orange-dark: #E56A10;    /* Dark orange */
    --cream: #FDF5E6;          /* Cream */
    --green-dino: #6BBF59;     /* Green */
    --green-dark: #4A9E3D;     /* Dark green */
}
```

### Editing Content

All content is directly in `index.html`. Look for these sections:
- `topic-item` - Edit topics
- `message-card` - Edit key messages
- `intro-text` - Edit intro paragraph

### Adding/Removing Topics

Each topic is a `topic-item` block. To add a new topic, copy an existing block and modify:
- `topic-number` - Topic number
- `topic-title` - Title
- `topic-description` - Description
- `topic-points li` - Bullet points

## Tech Stack

- **HTML5** - Structure
- **CSS3** - Styling and animations
- **JavaScript** - Interactivity (accordion)
- **Heebo Font** - Hebrew font from Google Fonts
- **Tabler Icons** - Icon library

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Features

- Fully responsive design
- Interactive accordion sections
- Smooth scroll animations
- RTL (Right-to-Left) Hebrew support
- No build process required - just HTML/CSS/JS

## License

Internal project for JUNIOREX podcast.

---

**JUNIOREX** - UX for Juniors
