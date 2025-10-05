# Learning-JavaScript
I am learning these from Shradha Khapra Mam (APNA_COLLEGE).
<br>
Author - InfinitezenCODER.
<br>
I am learning Javascript...
<br>
Connect JS to HTML as HTML is already connected to Browser.
<br>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body></body>
<script src="First.js">
 
</script>
</html>

First.js -

console.log("This is my first  Javascript Program");
let name="InfinitezenCODER";
console.log(name);
x= null;
console.log(x);
y=undefined;
console.log(y);
{
let age=19;
console.log(age);
}
{
let age=20;
console.log(age);
}
const Student=
{
fullNmae : "Swastik",
fan : "Zlatan Ibrahimnovic",
age : 19,
};
console.log(Student.Fan);
console.log(Student["age"]);
Student["age"]= Student["age"]+2;
console.log(Student.age);

console.log(Student.age);
const Profile = 
{
    User_name : "shradhakhapra",
    isFollow : true,
    Posts : 195,
    Followers : 569000 ,
    Following : 4 ,
    Name : "Shradha_Khapra",
    Profession : "Enterpreneur" ,
    Experience : "Ex-Microsoft_DRDO" ,
    Instituition : "Apnacollege" ,
    Moto : "TO EDUCATE SOMEONE IS THE HIGHEST PRIVILEGE" , 
}
console.log (Profile.Name);
console.log (Profile ["Experience"]);

// This Part Will Not be Executed.
/* This Part Will not be Executed. */

//Arithmatic Operators
let a = 2;
let b = 4;

console.log("a+b");
console.log(a+b);
console.log("a+b =", a+b);
console.log("a-b =", a-b);
console.log("a*b =", a*b);
console.log("a/b =", a/b);
console.log("a%b =", a%b);
console.log("a**b =", a**b);
console.log("a++=", a++);
console.log("a=", a);
console.log("++a=", ++a);

//Assignment Operators
let c = 10;
c+=5;
console.log("c+=5 =", c);
c-=5;
console.log("c-=5 =", c);
c**=2;
console.log("c**=2",c);
