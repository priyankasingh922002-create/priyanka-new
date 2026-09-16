# Priyanka Singh — Portfolio Website

Simple HTML/CSS/JS portfolio inspired by the reference design, built using
Priyanka's resume details.

## Run it (VS Code)

1. Unzip the folder and open it in VS Code.
2. Install the **Live Server** extension (if not already installed).
3. Right-click `index.html` → **Open with Live Server**.
   (Or just double-click `index.html` to open it in your browser.)

## Structure

```
priyanka-portfolio/
├── index.html      → all page content/sections
├── css/style.css    → all styling, colors, animations
├── js/script.js     → scroll reveal, nav, cursor glow, form, tilt effect
└── images/          → (empty — currently using placeholder images from picsum.photos)
```

## Replacing the placeholder images

All images currently load from `picsum.photos` (random stock photos), as requested.
To swap them with your own:

1. Put your image files inside the `images/` folder (e.g. `images/portrait.jpg`).
2. In `index.html`, find the `<img src="https://picsum.photos/...">` tags and
   replace the `src` with your local path, e.g. `src="images/portrait.jpg"`.

Images used (search `picsum.photos` in `index.html` to find all of them):
- Hero portrait
- 3 project thumbnails (Work section)
- Contact section visual

## Sections included

- Hero (intro + focus areas)
- Featured Work (3 placeholder project cards — replace with real projects)
- Skills & Tools
- Process (design workflow)
- About (education timeline + achievements + soft skills, pulled from your resume)
- Contact (form + your real contact details)

## Notes

- No fake client testimonials were added since there were none in your resume —
  the "Kind Words" section from the reference was replaced with an **Achievements**
  section using your real Certificate of Appreciation instead. Feel free to add
  testimonials later once you have real client/student feedback.
- The contact form is front-end only (shows a confirmation message on submit but
  doesn't send an email). Hook it up to a service like Formspree/EmailJS if you
  want real submissions.
