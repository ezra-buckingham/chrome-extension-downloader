# Chrome Extension Downloader

This project is a "fork" from https://gist.github.com/arulrajnet/2424bc1ffc40324f3786. I take no credit for most of this code, just adapted it to my needs.

Downloads a Chrome extension for you when given a URL to the chrome web store page.

## Usage

```
Usage: main.py [OPTIONS]

  Download CRX file from Google Chrome Webstore

Options:
  -u, --url TEXT     URL of the webstore page that shows you the "Add to
                     Chrome" button  [required]
  -o, --output TEXT  Where to write the extension out to
  --help             Show this message and exit.
```