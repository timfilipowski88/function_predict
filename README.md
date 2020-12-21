# function_predict
Predict the Output
Practice using a T-diagram to go through the following code snippets and predict the output.  Once you're done run your code and see if your prediction was correct.  Create a .js file with the code snippets and your predicted output and upload it once you're done.

Predict 1:

function greeting(){
    return "Hello";
    console.log("World");
}
var word = greeting();
console.log(word);

I think that this will just return with the word "Hello". 
The line with the "console.log("World");" will be ignored because the return statement ends the function. 


Predict 2: 

function add(num1, num2){
    console.log("Summing Numbers!");
    console.log("num1 is: " + num1);
    console.log("num2 is: " + num2);
    var sum = num1 + num2;
    return sum;
}
var result1 = add(3,5);
var result2 = add(4,7);
console.log(result1);
console.log(result2);

This will have outputs
"Summing Numbers!"
"num1 is: 3"
"num2 is: 5"
8
"Summing Numbers!"
"num1 is: 4"
"num2 is: 7"
11

--> I predicted the outputs correctly but had the wrong order because I forgot that the console.log will print with the function is called and the sum will print at the end. 


Predict 3: 

function highFive(num){
    for(var i=0; i<num; i++){
        if(i == 5){
            console.log("High Five!");
        }
        else{
            console.log(i);
        }
    }
}

The Function highFive if called with a num parameter of 6 or higher then it would console.log()
0
1
2
3
4
"High Five"
6...etc