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

console.log("This is my first  Javascript Program line.");
let name="InfinitezenCODER";//Always declare a variable using let.
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


//Comparison Operators
let c=7, d=8;
console.log("c==d",c==d);
console.log("c!=d",c!=d);
console.log("c===d",c===d);
console.log("c!==d",c!==d);
let e="9";
console.log("d===e",d===e);
console.log("d==e",d==e);

//Logical Operators
let x=9 ;
 y=10;
let cond1 = x>y;
let cond2 = x!=y;
console.log("cond1 && cond2 = ",cond1 && cond2);
console.log("cond1 || cond2 = ",cond1 || cond2);

//Conditional Statements.
let color;
if (mode === "dark")
{
    color="black";
}

// Eligible for Vote or not.
//If Statement
let age;
if (age>=18)
{
  console.log("You can vote");
}

// Even odd number .
// If-Else Statement
let num=5;
if (num%2==0)
{
    console.log("Even number")
}
else{
    console.log("Odd number")
}

// Color according to mode
// IF - else if Statement
let mode="light";
let  color;
if (mode==="dark")
{
    color = "blck";
}
else if(mode==="light")
{
    color="white";
}
else if(mode==="smoggy")
{
    color="grey";
}
else if(mode==="Foggy")
{
    color="light yellow";
}
else{
    color="light green";
}
console.log(color);

// Ternary Opeator
let Age=19,Result;
Result= Age>=18 ? "Adult" : "Not Adult"
console.log(Result);

//MDN DOCs.
// https://developer.mozilla.org/en-US/docs/Glossary/JavaScript. - For JavaScript Documentation
//To explore the documentation of all these things.
//  Visit the MDN Web Docs website.


console.log("Starting Loops");
// For Loops.
let i=1;
for(i=1;i<4;i++)
{
    console.log("I am going to nail it..\n")
}

let j,sum;
for(j=1,sum=0;j<=5;j++)
{
    sum=sum+j;
    console.log("Total summation is : ",sum);
}    
console.log("The loop has ended");


//While Loop
let z=1;
while(z<=3)
{
    console.log("z=",z);
    z++;
}

let n=21;
while(n<=20)
{
    console.log("n=",n);
    n++;
}

//Do-while Loop
let p=6;
do{
    console.log("p=",p);
    p++;
}while(p<=5);


//for-of loop
let nam="INFINITEZEN Coder",lenghth=0;
for(let val of nam)
{
    console.log("letter=",val);
    lenghth++;
}
console.log("Lenghth=",lenghth);


//for-in loop // Return keys.
let student = {
NAME: "Swastik",
isPass: true,

};

for(let i in student){
    console.log("key=",i);
    console.log("key=",i,"value=",student[i]);
}

//Designing a small luck based game using while loop.
//Practice Qs2.
let gameNUM=19;
let userNUM=prompt("Guess the Game Number");
while(userNUM!=gameNUM)
    {
   
userNUM = prompt("Enter another Number:"); // prompt se jo bhi input,ata hai woh string hota hai.So to check the equality of string we can not give '==='.
    }

console.log("Congratulations.You nailed it this Time.");


//Strings
let str1="Swastik";
let str2="InfinitezenCODER";
str1.length;
console.log(str1.length);
str1[0];
console.log("First letter of the string is :", str1[0]);


//Templet Literals
// How to write - let Var=`Text ${variable}`;
let myName='Swastik Patra';
let obj =
{
    NamE : "Pen",
    price : 10,
}
console.log("The cost of ",obj.NamE,"is","Rupees",obj.price);//Writting the line in basic way.
let Output= `The cost of ${obj.NamE} is Rupees ${obj.price}`; //Writting the same line using Templet Literals.
console.log(Output); // Printing the output.





