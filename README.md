# A4MP TECH RIDE – Website

Static website (HTML + CSS + JavaScript). No build tools needed.

## Run
Double-click `index.html`, or serve it:

    python3 -m http.server 8000

then open http://localhost:8000

(Internet is needed only for the icons, which load from Font Awesome CDN.)

## Structure
    index.html
    css/style.css
    js/script.js
    fonts/      Poppins (bundled)
    images/     logo, hero artwork, laptop image, project thumbnails

## Notes
- The desktop layout follows the 1672 x 941 design and scales with the browser width. Below 1000px it switches to a mobile layout.
- Replace any image in `images/` (same file name) to change it. Project thumbnails are in `images/projects/`.
- Social links: edit the `href="#"` values in the `.social` block of `index.html`.
- Watch Video link: edit the URL in `js/script.js`.
- Contact form (below the main screen): connect it to Formspree / EmailJS / your backend in `js/script.js`.
