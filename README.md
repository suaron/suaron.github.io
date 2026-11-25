# My Personal App

My Personal App: a personal-use app that works with Google account data. Static site on GitHub Pages: https://suaron.github.io/

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
└── favicon.svg
```

## Local preview

```
ruby -run -e httpd . -p 8000
```

Open http://localhost:8000
