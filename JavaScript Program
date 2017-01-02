<!DOCTYPE html>
<html>
 <head>
 <script language="JavaScript">
  function calculation() {
	var firstInput = parseInt(document.getElementById("first").value);
        var secondInput = parseInt(document.getElementById("second").value);
	var gate= document.getElementByID("gatetype").value;
	var total;
	
	
	if (gate === "AND"){ 
		var total = firstInput * secondInput
		document.getElementById("display").innerHTML = total;
		document.getElementById("picture").src = "AND.png";
	}
	else if (gate === "OR"){
		var total = firstInput + secondInput;
		If (total == 2){
			total=1;
		}
		document.getElementById("display").innerHTML = total;
		document.getElementById("picture").src = "OR.png";
	}
	else if (gate === "NAND"){
		var total = firstInput * secondInput;
		if (total = 0){
			total = 1;
			break;
		}
		else if (total = 1){
			total = 0;
		}
		document.getElementById("display").innerHTML = total;
		document.getElementById("picture").src = "NAND.png";
	}
	else if (gate === "NOR"){
		var total = firstInput + secondInput;
		if (total == 0){
			total = 1;
			break;
		else{
			total = 0;
		}
		document.getElementById("display").innerHTML = total;
		document.getElementById("picture").src = "NOR.png";
	}
	else{
		var total = firstInput + secondInput;
		if (total == 1){
			total=total;
		else{
			total = 0;
		}
		document.getElementById("display").innerHTML = total;
		document.getElementById("picture").src = "XOR.png";
	}
				
			
		
  }

 </script>
 </head>

<body>
 <p><b>Gate Simulator</b></p>
 <form>
  <label><b>Enter first digit</b></label>
  <select id="first">
  <option value="0">0</option>
  <option value="1">1</option>
  </select>
  <p>

  <label><b>Enter second digit</b></label>
  <select id="second">
  <option value="0">0</option>
  <option value="1">1</option>
  </select>
  <p>

  <label><b>Enter gate type</b></label>
  <select id=”gatetype”>
  <option value=”AND”>AND</option>
  <option value=”OR”>OR</option>
  <option value=”NAND”>NAND</option>
  <option value=”NOR”>NOR</option>
  <option value=”XOR”>XOR</option>
  </select>
 </form>

 <input type="submit" onclick="calculation();"><br/>
 <img id="picture" src="AND.png" width="100" height="100">
 <p>Output:</p>
 <p id="display">Input Answers</p>
</body>

</html>


