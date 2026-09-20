# Loan

A marketing landing page for a loan/financial service, built with HTML, Sass, and jQuery as a front-end practice project.

## Features

- Sections covering the offer, feed/testimonials, schedule, and how the service differs from competitors
- Image/testimonial sliders built with [Slick Carousel](https://kenwheeler.github.io/slick/)
- Video playback, a "download" action, and form handling
- Separate `modules.html` page

## Tech Stack

- HTML, Sass, jQuery, Slick Carousel
- Babel + core-js for JS transpilation/polyfills
- Gulp (build pipeline: HTML copy, asset copy, Sass compilation, JS bundling via Webpack) + Browsersync

## Getting Started

```bash
git clone https://github.com/korzinmark/loan_project.git
cd loan_project
npm install
npx gulp
```

`npx gulp` runs the default task (watch + build); compiled output goes to `dist/`.
