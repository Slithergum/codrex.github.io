# codrex.github.io
const inputBar=document.getElementById("input");
let mult=document.getElementById("mult");
let sub=document.getElementById("sub");
let add=document.getElementById("add");
let clr=document.getElementById("clear");
let equals=document.getElementById("eq");
let btn1=document.getElementById("btn1");
let btn2=document.getElementById("btn2");
let btn3=document.getElementById("btn3");
let btn4=document.getElementById("btn4");
let btn5=document.getElementById("btn5");
let btn6=document.getElementById("btn6");
let btn7=document.getElementById("btn7");
let btn8=document.getElementById("btn8");
let btn9=document.getElementById("btn9");
let btn0=document.getElementById("btn0");


var tempInputValue=0;

mult.onclick=function(){
  tempInputValue = "*";
  inputBar.value = inputBar.value+tempInputValue;
}
add.onclick=function(){
  tempInputValue = "+";
  inputBar.value = inputBar.value+tempInputValue;
}
sub.onclick=function(){
  tempInputValue = "-";
  inputBar.value = inputBar.value+tempInputValue;
}

clr.onclick=function(){

  inputBar.value = "";
}

btn1.onclick=function(){
  tempInputValue = 1;
  inputBar.value = inputBar.value+tempInputValue;
}

btn2.onclick=function(){
  tempInputValue = 2;
  inputBar.value = inputBar.value+tempInputValue;
}

btn3.onclick=function(){
  tempInputValue = 3;
  inputBar.value = inputBar.value+tempInputValue;
}

btn4.onclick=function(){
  tempInputValue = 4;
  inputBar.value = inputBar.value+tempInputValue;
}

btn5.onclick=function(){
  tempInputValue = 5;
  inputBar.value = inputBar.value+tempInputValue;
}

btn6.onclick=function(){
  tempInputValue = 6;
  inputBar.value = inputBar.value+tempInputValue;
}

btn7.onclick=function(){
  tempInputValue = 7;
  inputBar.value = inputBar.value+tempInputValue;
}

btn8.onclick=function(){
  tempInputValue = 8;
  inputBar.value = inputBar.value+tempInputValue;
}

btn9.onclick=function(){
  tempInputValue = 9;
  inputBar.value = inputBar.value+tempInputValue;
}

btn0.onclick=function(){
  tempInputValue = 0;
  inputBar.value = inputBar.value+tempInputValue;
}

equals.onclick=function(){
  let equals = 0;
  equals = eval(inputBar.value);
  inputBar.value = equals;
}


