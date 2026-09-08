# CyberCon CTF — Signal Board

## Running locally

Serve the folder instead of double-clicking `index.html` — some browsers
restrict what a page can do when opened directly from disk (`file://`),
and it also matches how the site behaves once deployed.

```bash
python -m http.server 8000
```

Then open http://localhost:8000 in your browser.
