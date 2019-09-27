# armory-tutorials

Tutorials for Armory3d game engine

## Building Docsify Locally
You can do it two way:
1. Doscify-cli
2. Python

after doing it. It should output something like:
```bash
Serving HTTP on 0.0.0.0 port x000 ...
```
and then open `http://localhost:x000` in your browser (with x as your port number).

### Docsify-cli
```bash
# Install docsify-cli
npm install -g docsify-cli
# go to root directory of this tutorial, then
docsify serve
```
Plus side of using docsify cli is that docsify will automatically reload your site for you on saving it.

### Python
```bash
# Make sure you have python, MacOS and Linux have Python 2.7 defaultly installed
# go to root directory of this tutorial, then
python -m SimpleHTTPServer
```
