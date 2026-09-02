# JSON Formatter

Paste JSON, get it validated and pretty-printed instantly. Runs entirely in your browser.

**Live:** <https://json-formatter.slippylabs.com/>

## What it does

- Pretty-print JSON with a configurable indent, or minify it back down.
- Validates as it goes and points at the syntax error when there is one.
- Copy the output in one click.

## Run it locally

A static site. No build step, no package manager, no dependencies:

```
git clone git@github.com:slippylabs/json-formatter.slippylabs.com.git
cd json-formatter.slippylabs.com
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

---

Part of [Slippy Labs](https://slippylabs.com). Every tool is indexed at
[projects.slippylabs.com](https://projects.slippylabs.com).
