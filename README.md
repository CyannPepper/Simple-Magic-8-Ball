# Simple-Magic-8-Ball
Conditionals practice in JavaScript main.js, making a simple Magic 8 Ball prompt.

let userName = '';
// Introductions to the user, named or not
userName === '' ? console.log('Hello!') : console.log('Hello, ' + userName + '!');
// displays user question
let userQuestion = 'Will I get that job?';
console.log('You asked: ' + userQuestion);
// generates random number between 0 & 7
let randomNumber = Math.floor(Math.random() * 8);

// randomly replies with an answer based on random number
let eightball = '';

switch (randomNumber) {
  case 0:
    console.log('It is certain');
    break;
   case 1:
    console.log('It is decidedly so');
    break;
     case 2:
    console.log('Reply hazy try again');
    break;
     case 3:
    console.log('Cannot predict now');
    break;
     case 4:
    console.log('Do not count on it');
    break;
     case 5:
    console.log('My sources say no');
    break;
     case 6:
    console.log('Outlook not so good');
    break;
     case 7:
    console.log('Signs point to yes');
    break;
     default: 
     console.log('Anything is possible...');
     break;
}
