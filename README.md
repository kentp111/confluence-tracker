# live — the DM's postings for the table screen

This branch carries one file, `latest.json`: the newest tracker seed or map scene blob the DM has
posted. The table page (the `main` branch, served by GitHub Pages) checks it on every refresh, and
from the **From the DM** button, and applies each posting once per machine.

Each posting replaces the last, and the commit history is the record. A blob is posted only at the
moment it is used, never ahead, because this repository is public.
