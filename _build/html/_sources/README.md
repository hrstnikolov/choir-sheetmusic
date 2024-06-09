# Choir Sheet Music Jupyter Book

Jupyter book accesible at https://hrstnikolov.github.io/choir-sheetmusic.

Draft version.

Steps to update the book:
1. Initial setup (do once at the start)
   1. Create python venv.
   2. Install dependencies `pip install jupyter-book ghp-import`.
2. Update book.
   1. Make changes.
   2. Run `jupyter-book build .` in the project directory. Shorthand is `jb build .` as jb is alias for jupyter-book.
   3. Commit changes and push to remote.
   4. Run locally `ghp-import -n -p -f _build/html`.
   5. After a minute, the changes shall be visible in https://hrstnikolov.github.io/choir-sheetmusic.

