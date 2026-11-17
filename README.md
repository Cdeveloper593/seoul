# SEOUL

A scroll-scrubbed journey through miniature Seoul, from dawn to night.

Serve this folder with any static HTTP server, for example `python3 -m http.server 8000`, then open `http://localhost:8000`. No build step or dependencies are required.

`index.html` contains the page styles and six-section `mountScrollWorld` configuration. It uses the existing, unchanged `scrub-engine.js`, posters at `assets/scene1.webp` through `scene6.webp`, and clips at `assets/vid/scene1.mp4` through `scene6.mp4` plus `conn1.mp4` through `conn5.mp4`.

Scroll to travel or use the section navigation. Posters remain visible until video frames are ready; the engine uses stills when reduced motion is preferred. The finale’s “Start your world” button links to https://cerium-web-development.vercel.app/.
