1. **HTML**

	1. Html文件默认代码    
	新建Html页面时，可直接使用下面的代码块来快速引用PDM6期页面所必须的css和Javascript
	```
	<!DOCTYPE html>
	<html lang="en">
		<head>
			<meta charset="UTF-8">
			<link rel="stylesheet" href="resources/vendor/bootstrap/css/bootstrap.min.css">
			<link rel="stylesheet" href="resources/vendor/bootstrap-table/bootstrap-table.css">
	    </head>
	    <body>
	        <script src="resources/vendor/jquery/jquery-1.11.2.min.js"></script>
	        <script src="resources/vendor/bootstrap/js/bootstrap.min.js"></script>
	    </body>
	</html>
	```
  	以上代码包括
	* Html文件类型的声明，让浏览器统一使用标准模式进行解析。
	* 指定了语言和网页字符编码
	* css文件和Javascript文件的引入位置
　　
	2. DOM属性顺序
	HTML 属性应当按照以下给出的顺序依次排列，确保代码的易读性。
	* class
	* id, name
	* data-*
	*　src, for, type, href
	×　title, alt
	×　aria-*, role

	
