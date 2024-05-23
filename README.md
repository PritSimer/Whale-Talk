# Whale-Talk
codecademy//js//beginners//practice
//let input = 'Cher is put';
let input = 'turpentine and turtles';
let vowels = ['a','e','i','o','u'];

let resultArray = [];

let resultString;

for (let i = 0; i < input.length; i++){
  if(input[i] === 'e'){
    resultArray.push(input[i]);
  }
   if(input[i] === 'u'){
    resultArray.push(input[i]);
  }
  for (let y = 0; y < vowels.length; y++){

if (input[i] === vowels[y]){
resultArray.push(input[i]);
}
}
};

resultString = resultArray.join('');

 console.log(resultString.toUpperCase());
