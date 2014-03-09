codeacademy_game
================

the first little javascript thing I made on codeacademy (they forced me to do the bieber reference..)

// Check if the user is ready to play!

confirm("Are you ready for awesomeness?");

age = prompt("No babies allowed. Input your age");
//age prompt
if(age < 13)
{
    console.log("Play at your own risk -- we're not responsible for whaever happens to you...");
}
else
{
    console.log("Congrats on being old enough to play Amy's first Javascript game! Rock on and enjoy.");
}
//printing out justin bieber story shiz
console.log("You are at a Justin Bieber concert, and you hear this lyric 'Lace my shoes off, start racing.' Unfortunately CodeAcademy forced me to write that. I know no one playing Amy's game would be at a Bieber concert..");
//sorry, you now have to talk to bieber
console.log("Suddenly, Bieber stops and says, 'Who wants to race me?'");
var userAnswer = prompt("Do you want to race Bieber on stage?");

//creating different scenerios
if(userAnswer==="yes")
{
 console.log("You and Bieber start racing. It's neck and neck! You win by a shoelace!");   
}
else
{
    console.log("Oh no! Bieber shakes his head and sings 'I set a pace, so I can race without pacing.'");
}
var feedback = prompt("Please rate this game on a scale 1 to 10; 1 being high and 10 being low.");
if(feedback>8)
{
    console.log("Thank you! We should race at the next concert!");
}
else
{
    console.log("I'll keep practicing coding and racing.");
}
