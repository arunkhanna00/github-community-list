# github-community-list

> Load profiles directly from files on GitHub and display them with JS only

This is just a demo to show how easy it is to load files directly from GitHub
in order to show them in custom-designed HTML pages.

This demo loads all files from this folder:
https://github.com/fullstackla/pairing-meetup/tree/master/community

The source code is fairly simple: [assets/app.js](assets/app.js).

This demo is using [jQuery](http://jquery.com/) for DOM access and AJAX requests
as well as [markdown.js](https://github.com/evilstreak/markdown-js) for
Markdown-to-HTML parsing.

## instructions

Clone the repository:
`git clone git@github.com:gr2m/github-community-list.git`

Change into that directory:
`cd github-community-list`

Run a server:
`python -m SimpleHTTPServer 8000`

Open in browser:
`http://localhost:8000`
