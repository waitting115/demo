<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>vue</title>
	<link rel="stylesheet" href="css/vue.css">
	<script src="js/vue.js"></script>
</head>
<body>
	<!-- vue-index是根容器 -->
	<div id="vue-index">
		<h1>{{ name }}</h1>
		<p>{{ job }}</p>

		<h1>{{ greet('afternoon') }}</h1>
	
		<!-- //绑定链接的方法 -->
		<a v-bind:href="websit">web开发</a><br>

		<input type="text" v-bind:value="name">
		<!-- 属性绑定 -->
		<p v-html="websitTag"></p>

		
	</div>
	







	<script src="js/index.js"></script>
</body>
</html>
