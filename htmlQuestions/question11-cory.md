* Why is it generally a good idea to position CSS `<link>`s between `<head></head>` and JS `<script>`s just before `</body>`? Do you know any exceptions?

  You generally want your css in the head so the css loads first and your page doesn't render without styling.

  You need to put your javascript files at the end of body because if you are adding event listeners or manipulating the DOM you will get an error if you run your script before the dom has been created.  Also javascript files are sometimes large and you want your page to load before executing them.
