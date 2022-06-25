<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Zuri Task</title>
</head>
<body>
<div id="myName"></div>

<script type="text/javascript">
		let operator = prompt('Enter operator ( either +, -, * or / ): ');

		let number1 = parseFloat(prompt('Enter first number: '));
		let number2 = parseFloat(prompt('Enter second number: '));

		let result;

		if (operator == '+') {
		    result = number1 + number2;
		}
		else if (operator == '-') {
		    result = number1 - number2;
		}
		else if (operator == '*') {
		    result = number1 * number2;
		}
		else {
		    result = number1 / number2;
		}
  
		alert(`${number1} ${operator} ${number2} = ${result}`);
</script>
</body>
</html>
