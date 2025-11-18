# Simple State Website

Static site highlighting major Florida cities. All distributable assets live in `public`, making it straightforward to serve the project with a lightweight static server or by opening `public/index.html` directly in a browser.

## Project Structure

```
public/
  assets/
    css/
      styles.css
    images/
      home/
      miami/
      orlando/
      tallahassee/
      icons/
  cities/
    miami.html
    orlando.html
    tallahassee.html
  contact-us.html
  index.html
```

## Getting Started

Open `public/index.html` in your browser or serve the `public` directory with any static web server (`python -m http.server 8080 -d public`, `npx serve public`, etc.).