# Honglin Wei - Portfolio Site

A small personal website with a mini crossword puzzle. It is built with only HTML and CSS (no JavaScript).

Repo: https://github.khoury.northeastern.edu/honglinwei/CS5610-Project_1

## Pages

| Page     | URL        | File                     |
| -------- | ---------- | ------------------------ |
| Home     | `/`        | `src/index.html`         |
| Puzzle   | `/game`    | `src/game/index.html`    |
| About    | `/about`   | `src/about/index.html`   |
| Contact  | `/contact` | `src/contact/index.html` |

## Folder structure

```
src/
  index.html          home page
  home.css            home page styles
  assets/
    css/styles.css    shared styles (variables, navbar, footer)
    images/           favicon and portrait
  game/               puzzle page + game.css
  about/              about page + about.css
  contact/            contact page + contact.css
```

Every page is an `index.html` inside its own folder, so the URLs don't end in `.html`.