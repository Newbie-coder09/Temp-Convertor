# Temp-Convertor

Temperature Converter, A utility Program that is very helpful and useful at the same time. This Repository has an HTML file that you can modify or use as it is in your website to add the utility of temperation convertion.


Benefits:
* You can simply modify the same code to do any other conversion.
* You can use this code in any school/college assignment or project.


Code(HTML+JS):

Add this to make it open it all browsers:

	<!doctype html>

Code:

	<html>

	<head>
		<title>Temperature Convertor</title>
		<script>
			function myFunction() {
				if(temp.value=="Celcius"){
					document.getElementById("paragraph").innerHTML = "Value in Fahrenheit= "+((input.value*1.8)+32).toFixed(2)+" And Kelvin= "+(parseFloat(input.value)+273.15).toFixed(2);
				}
				else if(temp.value=="Fahrenheit"){
					document.getElementById("paragraph").innerHTML = "Value in Celcius= "+((input.value-32)/1.8).toFixed(2)+" And Kelvin= "+(((input.value-32)/1.8)+273.15).toFixed(2);
				}
				else{
					document.getElementById("paragraph").innerHTML = "Value in Celcius= "+(parseFloat(input.value)-273.15).toFixed(2)+" And Fahrenheit= "+(((parseFloat(input.value)-273.15)*1.8)+32).toFixed(2);
				}
			}
        	</script>
	</head>
	        <link href="https://fonts.googleapis.com/css?family=Schoolbell&v1" rel="stylesheet">
	        <body style="background-color:lightblue;">
			<center>
			        <h1 style="font-family:'Schoolbell', arial, serif">Temperature Convertor</h1>
			        <img src="https://user-images.githubusercontent.com/119154806/236894300-bf522df6-7fd0-4ce2-8dd6-9e51cf183a4e.png">
			        <h2 style="font-family:'Schoolbell', arial, serif">Choose and enter value:</h2>
			        <select name="Temperature" id="temp" style="font-family:'Schoolbell', arial, serif">
				        <option value="Celcius">Celcius</option>
				        <option value="Fahrenheit">Fahrenheit</option>
				        <option value="Kelvin">Kelvin</option>
			        </select>
			        <input id="input" type="text" placeholder="Value" style="font-family:'Schoolbell', arial, serif"/>
			        <p id="paragraph" style="font-family:'Schoolbell', arial, serif">This code is purely written in HTML + JavaScript.</p>
			        <button type="button" onclick="myFunction()" style="font-family:'Schoolbell', arial, serif">Convert</button>
		        </center>
	        </body>
	</html>


Screenshots:
![Screenshot_20230509185448](https://github.com/Newbie-coder09/Temp-Convertor/assets/119154806/b31a4640-ba16-4fc5-abb9-575e25792e6a)
![Screenshot_20230509185458](https://github.com/Newbie-coder09/Temp-Convertor/assets/119154806/bce2f92a-2762-4317-b7cd-03451251c3a5)
![Screenshot_20230509185505](https://github.com/Newbie-coder09/Temp-Convertor/assets/119154806/636c97c3-0899-45a7-a1f0-ff78b0db9d25)
![Screenshot_20230509185513](https://github.com/Newbie-coder09/Temp-Convertor/assets/119154806/15740632-d6b4-48c4-8561-054707ad97b6)

**You can get the HTML file from files section**

Note:
This code is solely written by Ayush and you can use it as long as you don't consider it as yours'.

Please check my other repos too.
