# Dial

An espresso dial-in tool for a Baratza Encore ESP grinder and a Breville Bambino machine.

Everything is in a single file, `index.html`, written in Claude artifact format, so the `<!doctype>`, `<html>` and `<body>` wrappers are added when the page is published. Beans, shots and settings sync to each signed-in person's private `data/users/<id>/` space in the artifact's database (the `db` and `user` capabilities), with localStorage (`dial.v1`) as the offline cache. Gear photos stay in localStorage only.

Live version: https://claude.ai/artifact/XzfPxjFuQttqarGxw6UJs1
