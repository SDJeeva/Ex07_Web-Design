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
```
<html>
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
![Screenshot from 2023-05-30 08-50-12](https://github.com/SDJeeva/Ex07_Web-Design/assets/127816889/d6810c17-4f53-4b22-af05-6843b74119b2)
![Screenshot from 2023-05-30 08-50-09](https://github.com/SDJeeva/Ex07_Web-Design/assets/127816889/2a3782f7-bd58-4721-8371-83dfb7751163)




## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
