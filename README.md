# Open In Colab Chrome Extension - Firefox

This is a firefox port of [chrome extension](https://chrome.google.com/webstore/detail/open-in-colab/iogfkhleblhcpcekbiedikdehleodpjo) that, when clicked when viewing a Jupyter
notebook on github, will open that notebook in
[Google Colab](http://colab.research.google.com/).

## Installing the Extension

Install from Firefox Add-ons: https://addons.mozilla.org/en-US/firefox/addon/open-in-colab/

## Development Install

To install the extension directly from source:

1. Clone this repository to your local disk
2. install web-ext by running `npm i -g web-ext`
3. cd into extension dir and run `web-ext run`, it will open firefox with extension