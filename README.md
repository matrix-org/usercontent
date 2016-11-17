UserContent
===========

A way to render user generated content with a different origin to the main application.
This can be used to avoid XSS attacks.

Version 1
---------

```html
<html>
<head>
<script>
window.addEventListener("message", function(e){eval("("+e.data.code+")")(e)})
</script>
</head>
<body></body>
</html>
```
