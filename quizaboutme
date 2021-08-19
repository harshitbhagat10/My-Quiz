var readlineSync = require("readline-sync");
var score=0;

var userName = readlineSync.question("Enter your name! ")
console.log("Wellcome " + userName + " to the game!");

function quiz(question , answer){
  var useranswer = readlineSync.question(question)
  
  if (useranswer === answer){
  console.log("Correct!")
  score=score+1;
  }
  else{
  console.log("Incorrect!")
  }

console.log("Your Score is: ", score)
console.log("----------------------")
}


var questions = [{
  question: "What is my name? " , answer: "Harshit"},{question: "What is my age? " , answer: "20"},{
  question: "Where do I live? " , answer: "Bangalore"},{question: "Where do I study? " , answer: "BIT"}
]
for (var i=0; i<questions.length; i++){
  quiz(questions[i].question ,questions[i].answer)

}

console.log("Your final score is: " + score)