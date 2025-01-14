# operatorsJs
var temperature;
temperature = 56;
if (temperature < 20) {
    console.log("its cold outside");
}
if (temperature < 30) {
    console.log("its moderate outside");
} else {
    console.log("its hot");
}

//logical conditional logic
var email= true;
var facebook = false;
var google = false;

if(email || facebook || google)
{
console.log("login success");
}


var authenticaion= true;
if(authentication){
console.log("show signout button");
}
else{
console.log("show login option");
}


// functions
function sayHello(name){
console.log("hello there, Hitesh");
console.log(`Hello`, $(name));
}
sayHello("Hitesh");

function namste()
{
return "hello in India";
}

var greeting = namste();
console.log(greeting);
console.log(namste);
 






