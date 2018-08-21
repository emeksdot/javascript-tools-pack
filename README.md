# javascript-tools-pack
A javascript language tools pack for reusable code such as for-loops, while-loops, functions for implementing a range algorithm etc.
A basic for loop over an array:

var arrayOfStrings = ["GOOSE", "BUMPS", "CAN'T", "SCREAM"];

for (let i = 0; I < arrayOfStrings.length; i++){
  console.log(arrayOfStrings[i]);
};

The same result achieved using a while loop:

var count = 0;
while (count < arrayOfStrings.length){
  console.log(arrayOfStrings[count]);
  count += 1;
};

