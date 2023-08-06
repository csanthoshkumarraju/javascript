# javascript
<!-- <!DOCTYPE html>
<html>
<body>

<h2>JavaScript in Body</h2>

<p id="demo"></p>

<script>
document.getElementById("demo").innerHTML = "My First JavaScript";
</script>

</body>
</html> 
 -->
<!-- <!DOCTYPE html>
<html>
<body>
<script>
function myFunction() {document.getElementById("demo").innerHTML = "calling function";}
</script>
<h2>Js in head</h2>
<p id="demo">A paragraph</p>
<button type="button" onclick="myFunction()">Click</button>
</body>
</html>                   -->
<!-- <!DOCTYPE html>
<html>
<body>
<h2>Js in head</h2>
<p id="demo">A paragraph</p>
<button type="button" onclick="myFunction()">Click</button>
<script>
function myFunction() {document.getElementById("demo").innerHTML = "calling function";}
</script>
</body>
</html>   -->

<!--  Java script output-->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>Header</h1>
<p>Paragraph</p>  
<p id="demo"></p>
<script>
document.getElementById("demo").innerHTML = 5 + 6;
</script>
</body>
</html>    -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>Header</h1>
<p>Paragraph</p>  
<script>
document.write(5 + 6);
</script>
</body>
</html>   
 -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>Header</h1>
<p>Paragraph</p>  
<button type="button" onclick="document.write(5 + 6)">Click</button>
</body>
</html>   
 -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>Header</h1>
<p>Paragraph</p>  
<script>window.alert(5+6)</script>
</body>
</html>   

 -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>Header</h1>
<p>Paragraph</p>  
<script>alert(5+6)</script>
</body>
</html>  -->
<!-- <!DOCTYPE html>
<html>
<body>
<script>
console.log(5+6);
</script>
</body>
</html>  -->
<!-- <!DOCTYPE html>
<html>
<body>
<h2> window.print() method<h2>
<p>Click the button to print the page</p>
<button onclick="window.print()">print</button>
<script>
console.log(5+6);
</script>
</body>
</html>  -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>Arithmetic opereation</h1>
<p>Javascript program to calculate arithmetic operations</p> 
<p id="demo"></p>
<script>
let x,y,z;
x=4;
y=3;
z = x + y;
s = x - y;
m = x * y;
d = x / y;
p = x ** y;
document.getElementById("demo").innerHTML = x + ' + '+ y +' = ' + z + '    ' + x + ' - '+ y +' = ' + s + '    ' +x + ' * '+ y +' = ' + m + '    ' +x + ' / '+ y +' = ' + d + '   ' +x + ' ** '+ y +' = '+ p;
</script>
</body>
</html> -->

<!-- <!DOCTYPE html>
<html>
<body>
<h1>Arithmetic operation</h1>
<p>Javascript program to calculate arithmetic operations</p> 
<p id="demo"></p>
<script>
var x,y,z;
x=4;
y=3;
z = x + y;
s = x - y;
m = x * y;
d = x / y;
p = x ** y;
document.getElementById("demo").innerHTML = x + ' + '+ y +' = ' + z + '    ' + x + ' - '+ y +' = ' + s + '    ' +x + ' * '+ y +' = ' + m + '    ' +x + ' / '+ y +' = ' + d + '   ' +x + ' ** '+ y +' = '+ p;
</script>
</body>
</html> -->

<!-- <!DOCTYPE html>
<html>
<body>
<h1>String concatenation</h1>
<p id="demo"></p>
<script>
let x = 'Chiluru' + ' Santhosh ' + ' kumar ' + ' raju '
document.getElementById("demo").innerHTML = x; 
</script>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>String concatenation</h1>
<p id="demo"></p>
<script>
let x = '5' + 4 + 6
document.getElementById("demo").innerHTML = x; 
</script>
</body>
</html>
 -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>String concatenation</h1>
<p id="demo"></p>
<script>
let x =  4 + 6 + ' volvos'
document.getElementById("demo").innerHTML = x; 
</script>
</body>
</html> -->
<!-- JS function -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>function</h1>
<p id="demo"></p>
<script>
function multiply(v1, v2) { 
  return v1 * v2 ;
}
let result = multiply(10,5);
document.getElementById("demo").innerHTML = result; 
</script>
</body>
</html> -->
<!--Js objects -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>function</h1>
<p id="demo"></p>
<script>
const car = {type:"BMW",model:"600",color:"white"} 
document.getElementById("demo").innerHTML = 'The car color is '+ car.color; 
</script>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>function</h1>
<p id="demo"></p>
<script>
const person = {
       first_name :'Chiluru',
       middle_name :'Santhosh Kumar',
       last_name :'Raju',       
} 
document.getElementById("demo").innerHTML = 'The full name is '+ person.first_name + ' '+person.middle_name +' '+person.last_name; 
</script>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>function</h1>
<p id="demo"></p>
<script>
const person = {
       first_name :'Chiluru',
       middle_name :'Santhosh Kumar',
       last_name :'Raju',       
} 
document.getElementById("demo").innerHTML = 'The full name is '+ person['first_name'] + ' '+person['middle_name']+' '+person['last_name']; 
</script>
</body>
</html>

 -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>function</h1>
<p id="demo"></p>
<script>
const person = {
       first_name :'Chiluru',
       middle_name :'Santhosh Kumar',
       last_name :'Raju',}
       function full_name(){ return this.first_name + ' '+this.middle_name +' '+  this.last_name; }
document.getElementById("demo").innerHTML = full_name; 
</script>
</body>
</html>
 -->

<!--  event based Js-->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
<button onclick="document.getElementById('demo').innerHTML = Date()">The time is?</button>
</script>
</body>
</html> --> 
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
document.getElementById('demo').innerHTML = Date()
</script>
</body>
</html>  -->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<button type="button" onclick="Current_Date()">Click to get Current_Date</button>  
<script>
function Current_Date() {
 document.getElementById("demo").innerHTML = Date() 
}
</script>
</body>
</html> -->
<!-- JS strings -->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
let First_name = "Chiluru";
let Middle_name = "Santhosh Kumar";
let Last_name = "Raju";
let Full_name = "Chiluru Santhosh Kumar Raju";

document.getElementById("demo").innerHTML = ' First name is : ' + First_name + '<br>' +' middle name is :'+ Middle_name + '<br>' +' Last name is: ' + Last_name + '<br>' +' Full name is : ' + Full_name
</script>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
let Full_name = "Chiluru Santhosh Kumar Raju";
let length =  Full_name.length
document.getElementById("demo").innerHTML = ' Full name is : ' + Full_name + '<br> '+ 'length of string is :' + length
</script>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
let Full_name = "Chiluru Santhosh Kumar Raju";
let length =  Full_name.length
document.getElementById("demo").innerHTML = ' Full name is : ' + Full_name + '<br> '+ 'length of string is :' + length
</script>
</body>
</html>
 -->
<!-- Js arrays -->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
const cars = ['Tata','Mahindra','BMW','Volvo']
document.getElementById("demo").innerHTML = cars
</script>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
const cars = []
cars[0] = 'Tata'
cars[1] = 'Mahindra'
cars[2] = 'BMW'
cars[3] = 'VOLVO'
document.getElementById("demo").innerHTML = cars
</script>
</body>
</html>
 -->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
const cars = new Array('Tata','Mahindra','BMW','Volvo')
document.getElementById("demo").innerHTML = cars
</script>
</body>
</html>
 -->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
const cars = new Array('Tata','Mahindra','BMW','Volvo')
document.getElementById("demo").innerHTML = cars.sort()
</script>
</body>
</html> -->
<!-- JS math -->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
// document.getElementById("demo").innerHTML = Math.PI;
// document.getElementById("demo").innerHTML = Math.round(4.2)
// document.getElementById("demo").innerHTML = Math.ceil(2.7)
// document.getElementById("demo").innerHTML = Math.floor(2.7)
// document.getElementById("demo").innerHTML = Math.trunc(2.7)
// document.getElementById("demo").innerHTML = Math.sign(2.7)
// document.getElementById("demo").innerHTML = Math.sign(-7)
// document.getElementById("demo").innerHTML = Math.sign(0)
// document.getElementById("demo").innerHTML = Math.pow(2,7)
// document.getElementById("demo").innerHTML = Math.sqrt(36);
// document.getElementById("demo").innerHTML = Math.abs(-7.9);
// document.getElementById("demo").innerHTML = Math.min(1,2,3,4,5,6);
// document.getElementById("demo").innerHTML = Math.max(1,2,3,4,5,6);
document.getElementById("demo").innerHTML = Math.random();
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
document.getElementById("demo").innerHTML = Boolean(10 > 9);
</script>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
let x = 4;
document.getElementById("demo").innerHTML = (x == 8);
</script>
</body>
</html> -->

<!-- JS Java script conditions -->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
let x = 14;
let y = 14;
let large_number;
if ( x > y ) { large_number = ' large number is :- ' + x;}
else if ( x < y ) { large_number = ' large number is :- ' + y;}
else { large_number = ' equal numbers :- ' + y;}
document.getElementById("demo").innerHTML = large_number;
</script>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
const time = new Date().getHours();
let greet;
let y = 14;
if ( time < 7 ) { greet = ' time is  ' +  time + ' <br> ' + ' Good Morning';}
else if ( time < 13 ) { greet = ' time is  ' +  time + ' <br> ' + ' Good Afternoon';}
else if ( time < 17 ) { greet = ' time is  ' +  time + ' <br> ' + ' Good Evening';}
else { greet = ' time is  ' +  time + ' <br> ' + ' Good day';}
document.getElementById("demo").innerHTML = greet;
</script>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<body>
<p id="demo"></p>
<script>
let Day;
  switch (new Date().getDay()){
    case 0:
      Day = 'Sunday';
      break;
    case 1:
      Day = 'Monday';
      break;
    case 2:
      Day = 'Tuesday';
      break;
    case 3:
      Day = 'Wednesday';
      break;
    case 4:
      Day = 'Thursday';
      break;
    case 5:
      Day = 'Friday';
      break;
    case 6:
      Day = 'Saturday';
      break;
  }
document.getElementById("demo").innerHTML = ' Today is ' + Day;
</script>
</body>
</html> -->
<!-- JS loops -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>for loop</h1>
<p id="demo"></p>
<script>
const cars = ['Tata','MAhindra','BMW']; 
let text = '';
for (let i = 0;i < cars.length;i++) {text += cars[i]+ "<br>";}
document.getElementById("demo").innerHTML = text; 
</script>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>while loop</h1>
<p id="demo"></p>
<script>
const cars = ['Tata','MAhindra','BMW']; 
let text = '';
let i =0;
while ( i < cars.length) {text += cars[i]+ "<br>";i++ }
document.getElementById("demo").innerHTML = text; 
</script>
</body>
</html> -->
<!-- <!DOCTYPE html>
<html>
<body>
<h1>while loop</h1>
<p id="demo"></p>
<script>
let text = '';
let i =0;
while ( i < 10) {text+=i+ "<br>";i++ }
document.getElementById("demo").innerHTML = text; 
</script>
</body>
</html> -->

