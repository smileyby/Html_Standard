HTML规范 - 整体结构
==============
#####HTML基础设施#####
*	文件应以“<!DOCTYPE..............>”首行顶格开始，推荐用“<!DOCTYPE html>”.
*	必须申明文档的编码charset，且与文件本身编码保持一致，推荐使用UTF-8编码<meta charset="utf-8">。
*	根据页面的内容和需求填写适当的keywords和description。
*	页面title是极为重要的不可缺少的一项。

>
```html
	<!DOCTYPE html>
	<html>
	<head>
	<meta charset="utf-8"/>
	<title>NEC：更好的CSS方案</title>
	<meta name="keywords" content=""/>
	<meta name="description" content=""/>
	<meta name="viewport" content="width=device-width"/>
	<link rel="stylesheet" href="css/style.css"/>
	<link rel="shortcut icon" href="img/favicon.ico"/>
	<link rel="apple-touch-icon" href="img/touchicon.png"/>
	</head>
	<body>
	</body>
	</html>
```