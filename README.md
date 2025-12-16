These are js coding problems

##Reverse a string

const reverseString = str => str.split("").reverse().join("");
console.log(reverseString("word"));
------------------
function reverseString (word){
    let rString = "";
    for(let i = word.length - 1; i >= 0; i--){
        rString = rString + word[i];
    }
    return rString;
}
console.log(reverseString("word"));
---------------------
function reverseString (word){
    return rString = [...word].reverse().join("");
    
}
console.log(reverseString("word"));
