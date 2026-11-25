# Private Google App

A personal-use Google app, published publicly. Static site on GitHub Pages: https://suaron.github.io/app/

## Structure

```
.
├── index.html                   # home page
├── 404.html                     # not-found page
├── privacy.html                 # Privacy Policy
├── terms.html                   # Terms of Service
├── .nojekyll                    # disables Jekyll processing
├── assets/
│   ├── css/style.css
│   ├── js/main.js
│   └── images/logo.svg
├── favicon.svg
└── .github/workflows/pages.yml  # deploys to Pages on push to main
```

## Local preview

```
ruby -run -e httpd . -p 8000
```

Open http://localhost:8000
