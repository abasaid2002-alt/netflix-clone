# Netflix Clone (React)

Netflix-style frontend clone built with React, Vite and Bootstrap. The app fetches movie posters from the OMDb API and displays them in responsive galleries.

## Technologies
- React
- Vite
- JavaScript
- Bootstrap
- Bootstrap Icons
- OMDb API

## Main features
- Netflix-inspired dark UI layout
- Reusable components (Navbar, Gallery, MovieCard, Footer)
- Multiple movie sections:
  - Trending Now
  - Watch it Again
  - New Releases
- API fetch from OMDb (`s=` search query)
- Loading spinner while fetching data
- Responsive movie grid
- Hover effect on movie cards

## Project structure
- `src/components/Gallery.jsx` → fetches movie lists from OMDb
- `src/components/MovieCard.jsx` → renders poster cards
- `src/omdbConfig.js` → OMDb base URL and API key config

## Project goal
Project created during the Front-End path at Epicode to practice React components, props, API calls and responsive UI layout with Bootstrap.

## Run locally
```bash
npm install
npm run dev
