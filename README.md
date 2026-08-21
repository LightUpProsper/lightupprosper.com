# Light Up Prosper v1.4.1 hotfix

Fixes the Home navigation/cache mismatch seen after opening project pages.

Changes:
- Home and logo links now return to `/` instead of `/index.html`.
- CSS and JS use versioned URLs (`?v=1.4.1`) so browsers fetch the matching current files instead of a stale cached copy.

Upload all files to the repository root, replacing matching files.
