# TIL
if (I want to import something )
import {add, subtract} from "./math_functions.js";

if(I want to import all the files as some variable name)
import * as myMathModule from "./math_functions.js";

if (I want to access some function inside that variable)
myMathModule.add(2,3)

if(I want to export default funtion)
export default function subtract(x, y) {
    return x-y;
}

if (i want to import the default function)
import subtract from "./dljsl.js";
without the {}

When the task completes, you either fulfil your promise or fail to do so.

promise has 3 states
pending
fufilled
rejected

if(I want to make a Promise)
const myPromise = new Promise ((resolve, reject) => {
    if (condition){
        resolve ("Promise was fulfilled");
    } else {
        reject ("Promise was rejected");
    }
});

{Handle a Fulfilled Promise with then}
myPromise.then(result =>{
  console.log(result);
});

{Handle a Rejected Promise with catch}
myPromise.catch(error =>{
    console.log(error);
});

{Using the Test Method}
let testStr = "";
let testRegex = / /;
testRegex.test(testStr);

{Match Literal Strings}
regex has to match with the test string for it to be true

{Match a Literal String}
/dog|cat|fish/;

{Ignore Case While Matching}
/ignorecase/i;

{Deleting white space}
string = "    Hello World!     ";
Regex = /^\s+|\s+$/;
string.update(Regex, "");