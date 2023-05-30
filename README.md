# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>
```
## OUTPUT
![calcul sc-1](https://github.com/Thennunagaraj/Ex07_Web-Design/assets/128386061/7ff812cb-ffe6-4d7d-b211-d7812bda7acc)
![calcul sc-2](https://github.com/Thennunagaraj/Ex07_Web-Design/assets/128386061/da8020f1-ac9c-4ecc-93f0-af48127dce7a)
![calcul sc-3](https://github.com/Thennunagaraj/Ex07_Web-Design/assets/128386061/ac13d812-582d-4618-ab04-f52a0795d102)
![cacul sc -4](https://github.com/Thennunagaraj/Ex07_Web-Design/assets/128386061/1ee996e9-c83d-4232-9573-bbf47f5f47fd)
![calcul sc-5](https://github.com/Thennunagaraj/Ex07_Web-Design/assets/128386061/c9e44faf-2833-4eac-95aa-a9e3b77fcac6)


## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
