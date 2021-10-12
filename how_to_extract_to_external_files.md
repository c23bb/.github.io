# How to extract CSS/JS from HTML

CSS and JS can be extracted from HTML

We can do this pretty easily using `<link>` and `<script>` tags.

We use a `link` tag for connecting CSS (among other things)

```html
<link rel="stylesheet" href="LOCATION.css" />
```
`LOCATION.css` is the place where the CSS file lives. `/` seperates directories, and `/` is the root directory of the project.a


We can use a `script` tag to connect JS
```html
<script type="text/javascript" src="LOCATION.js"></script>
```

(note that we close the script tag, but the link tag closes itself. This is a remnant of the origins of hypertext.)

---

## Starting a server
Now that we have references, browsers prevent you from accessing other files without starting a server for security purposes. 

You can easily start a server with Python.

Open terminal (in the project directory) and type:

```shell
python -m SimpleHTTPServer
```

A server will start on [port 8000](https://localhost:8000).

yay.