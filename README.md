# Redshift A Cappella Concert Site

This is a simple static website for the Redshift a cappella concert on **May 31 at 6:00 PM**, held at the Palo Alto High School Media Arts Center.

The site is built using Hugo, a fast static site generator.

---

## 📍 Event Details

* **Group:** Redshift A Cappella
* **Date:** May 31
* **Time:** 6:00 PM
* **Location:** Palo Alto High School Media Arts Center
* **Address:** 50 Embarcadero Rd, Palo Alto, CA

---

## 🚀 Development

### Prerequisites

* Install Hugo (extended version recommended)

On macOS (Homebrew):

```bash
brew install hugo
```

---

### Run locally

```bash
hugo server -D
```

Then open:

```
http://localhost:1313
```

---

### Build the site

```bash
hugo
```

The generated site will be in:

```
public/
```

---

## 📁 Project Structure

```
.
├── content/           # Markdown content (homepage is _index.md)
├── layouts/           # HTML templates
│   ├── _default/
│   │   ├── baseof.html
│   │   └── home.html
│   └── partials/
│       └── head.html
├── static/
│   ├── css/
│   │   └── site.css
│   └── images/
│       └── redshift.jpg
├── hugo.toml          # Site configuration
└── public/            # Generated output (not committed)
```

---

## 🌐 Deployment

This is a static site and can be hosted on:

* Netlify
* GitHub Pages (with a build step)
* Any static web host

Typical deployment flow:

1. Push repository
2. Hosting platform runs `hugo`
3. Serve contents of `public/`

---

## 📝 Notes

* The `public/` directory is generated and should **not** be committed
* Images go in `static/images/`
* CSS lives in `static/css/site.css`

---

## 🤖 AI Assistance

Portions of this project (including initial scaffolding, layout, and styling) were generated with the assistance of ChatGPT.

---

## 📄 License

MIT License
