# SSCCE demonstrating issues building Elm 0.19 projects in parallell

To trigger the issue run `npm run build`. The issue appears every second run on my MBP.

```
lerna ERR! npm run build stderr:
-- CORRUPT DEPENDENCY ----------------------------------------------------------

I ran into a problem while building the following package:

    elm/core 1.0.0

This probably means the downloaded files got corrupted somehow. Try deleting
/Users/smu/go/src/repo.jazznetworks.com/jazz/main/frontend/elm-home (a directory
for caching build artifacts) and see if that resolves the issue.
```
