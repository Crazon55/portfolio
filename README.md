# Portfolio - Interactive Automation City

An interactive portfolio website built with Phaser.js where visitors can navigate through different zones to explore projects, experience, and skills.

## Features

- 🎮 Interactive driving mechanics with WASD/Arrow keys
- 🗺️ Multiple zones to explore:
  - Command Center (Profile)
  - Owled Tower (Current Job)
  - Marty Labs (Internship)
  - R&D Facility (Projects)
  - Power Grid (Tech Stack)
- 📱 Responsive design
- ⚡ Smooth animations and transitions

## Deployment on Render

This is a static site that can be deployed directly on Render:

1. **Create a new Static Site on Render:**
   - Go to [Render Dashboard](https://dashboard.render.com)
   - Click "New +" → "Static Site"
   - Connect your GitHub repository
   - Select this repository

2. **Build Settings:**
   - **Build Command:** (leave empty, it's a static HTML file)
   - **Publish Directory:** `/` (root directory)
   - **Environment:** Static Site

3. **Deploy:**
   - Render will automatically deploy your site
   - Your site will be available at `https://your-app-name.onrender.com`

## Local Development

Simply open `portfolio.html` in your web browser, or use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then open `http://localhost:8000/portfolio.html` in your browser.

## Controls

- **WASD** or **Arrow Keys**: Drive the car
- **Park on a zone**: Automatically opens the modal with information
- **Escape** or **X**: Close modal
- **Back button**: Navigate back from project details

## Technologies Used

- Phaser.js 3.60.0
- HTML5
- CSS3
- Vanilla JavaScript
