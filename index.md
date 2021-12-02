<!DOCTYPE html>
<html>
	<head>
		<title>Калькулятор</title>
		<script defer src="script.js"></script>

	<style>
	body {
  		padding: 0;
  		margin: 0;
  		background: linear-gradient(to right, #123123, #4444);
  		display: grid;
  		justify-content: center;
  		align-content: center;
  		min-height: 95vh;
  	}
  	input{
    	background-color: rgba(255, 255, 255, 0.75);
		height: 20px;
	}

	input:hover{
    	background-color: #4444;
	}

	button{
    	border: 1px solid white;
    	background-color: rgba(255, 255, 255, 0.75);
    	width: 40px;
 		height: 40px;
 		margin-left: 100px;
	}

	button:hover {
    	background-color: #4444;
	}
  	</style>
	</head>
	<body>
		<p>Первое число<input type="text" id="n1"></p>
		<p>Второе число<input type="text" id="n2"></p>
		<button onclick="plus()">+</button>
		<button onclick="minus()">-</button>
		<button onclick="multiplication()">X</button>
		<button onclick="division()">/</button>
		<hr>
		<p>Результат: <span id="out"></span></p>
	</body>
</html>  
  
