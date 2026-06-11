# After the Bell

A static digital counterstory website about poverty, work, language, and education. It now uses a short sequence of full-screen image panels with minimal text for a faster read.

## Files

- `index.html` contains the story and source links.
- `styles.css` creates the full-screen panel layout and image treatment.
- `script.js` handles the reading progress bar.
- `assets/` contains the local images used by the website.

## Research note

Mia is a fictional composite character. The story is based on patterns from student-voice reporting and statistics from the NCES `Report on the Condition of Education 2024`.

## Cache-busting

The page uses versioned asset URLs like `styles.css?v=20260610-1` so GitHub Pages and browsers are less likely to serve stale CSS, JavaScript, or images after a new push. When updating the site, bump that version string in `index.html`.

## Slide photo slots

If you want each story slide to use a different local photo, add files with these names inside `assets/`:

- `slide-counselor.jpg`
- `slide-work.jpg`
- `slide-study.jpg`
- `slide-test.jpg`

The CSS in `styles.css` is already set up to pick them up automatically.
