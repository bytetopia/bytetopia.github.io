## aka.ci

aka.ci makes your url short and easy to remember.

### add

add file -> create new file -> enter file name: YOUR_SHORT_SUFFIX/index.html

-> copy and modify template code:

```html
<html>
<head>
	<title>Redirecting ...</title>
	<meta name="viewport" content="width=device-width,initial-scale=1">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <script src="script.js"></script>
</head>
<body>
	<script language="javascript" type="text/javascript">
	      setTimeout(function f(){
	        window.location.href="REPLACE_THIS_REPLACE_THIS"; 
	      }, 10);
	</script>
</body>
</html>
```
