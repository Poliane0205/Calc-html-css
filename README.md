<html>
	<head>
		<title>HTML Calculator</title>
		<style> 
			html {
				  font-size: 40px;
				}
			input{
				 font-size: 40px;
				}
		</style>
	</head>
	<body bgcolor= "# 000000" text= "Yellow">
		<form name="calculator" ><input type="button" value="1" onClick="document.calculator.ans.value+='1'">
			<input type="button" value="2" onClick="document.calculator.ans.value+='2'">
			<input type="button" value="3" onClick="document.calculator.ans.value+='3'">
			<input type="button" value="+" onClick="document.calculator.ans.value+='+'"> <br/>
			<input type="button" value="4" onClick="document.calculator.ans.value+='4'">
			<input type="button" value="5" onClick="document.calculator.ans.value+='5'">
			<input type="button" value="6" onClick="document.calculator.ans.value+='6'">
			<input type="button" value="-" onClick="document.calculator.ans.value+='-'"> <br/>
			<input type="button" value="7" onClick="document.calculator.ans.value+='7'">
			<input type="button" value="8" onClick="document.calculator.ans.value+='8'">
			<input type="button" value="9" onClick="document.calculator.ans.value+='9'">
			<input type="button" value="*" onClick="document.calculator.ans.value+='*'"> <br/>
			<input type="button" value="/" onClick="document.calculator.ans.value+='/'">
			<input type="button" value="0" onClick="document.calculator.ans.value+='0'">
			<input type="reset" value="Reset"> <br/>
			<input type="button" value="=" onClick="document.calculator.ans.value=eval(document.calculator.ans.value)">Solução 
			<input type="textfield" name="ans" value="">
		</form>
	</body>
</html>
