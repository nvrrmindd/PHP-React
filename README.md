# Seminar #3: Basic HTML and CSS

## IoT Healthcare Monitoring

A modern one-page healthcare dashboard for monitoring metabolic syndrome with IoT sensors.

## Features

- Introduction header with navigation menu
- Patient information table
- Patient dashboard with five health parameters:
  - Body temperature
  - Blood glucose
  - Heart rate
  - Blood pressure
  - ECG
- Sensor cards with sensor name, measured value, unit, and status
- Normal and abnormal alert examples
- Responsive mobile layout
- Medical background image and transparent dashboard panels

## Technologies

- HTML5
- CSS3
- CSS Grid
- Responsive media queries
- Hover effects and CSS transitions

## Validation

- HTML checked with HTML Tidy: no errors
- CSS checked in VS Code diagnostics: no errors

## Run Locally

From the project folder, run:

```bash
python3 -m http.server 8002
```

Then open:

```text
http://localhost:8002/
```

## Public Website

[Open the GitHub Pages website](https://nvrrmindd.github.io/PHP-React/)

## Screenshots

Screenshots for the assignment are stored in [`screenshots/seminar-3/`](screenshots/seminar-3/).

Add the following files to that folder:

- `desktop.png` - final page on a desktop viewport
- `mobile.png` - final page on a mobile viewport
- `html-validation.png` - HTML validation result
- `css-validation.png` - CSS validation result

## Project Files

- `index.html` - page structure and content
- `style.css` - layout, colors, backgrounds, cards, navigation, hover effects, and responsive styles
