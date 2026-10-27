# LDraw Parts Library mirror

A static copy of the official [LDraw.org](https://www.ldraw.org/) Parts Library (`parts/`, `p/` and `LDConfig.ldr`), served with GitHub Pages so Brick Studio can convert LDraw models in the browser.

The parts are the work of the LDraw.org community, licensed under CC BY 2.0 and CC BY 4.0 (see `CAreadme.txt`, `CAlicense.txt`, `CAlicense4.txt`). This mirror is not affiliated with LDraw.org.

## File list

`files.txt` lists every part and primitive path (one per line), so clients can find a file in one request instead of probing folders.

## Updating

Download the latest `complete.zip` from ldraw.org, replace `parts/`, `p/` and `LDConfig.ldr` with the new copies, regenerate the file list with `find parts p -type f -name '*.dat' | sort > files.txt`, then commit and push.
