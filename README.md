# Choir Sheet Music Jupyter Book

Jupyter book accesible at https://hrstnikolov.github.io/choir-sheetmusic.

Draft version.

Steps to update the book:
1. Initial setup (do once at the start)
    1. Create python venv.
    1. Install dependencies `pip install jupyter-book ghp-import`.
1. Update book.
    1. Make changes.
    1. Run `jupyter-book build .` in the project directory. Shorthand is `jb build .` as jb is alias for jupyter-book.
    1. Commit changes and push to remote.
    1. Run locally `ghp-import -n -p -f _build/html`.
    1. After a minute, the changes shall be visible in https://hrstnikolov.github.io/choir-sheetmusic.

