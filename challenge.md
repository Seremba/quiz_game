let us buid a fun quiz game.

1. build a function constructor called Question to describe a queestion: A question should include;
2. a) question itself
3. b) the answers from which the player can choose the correct one(choose an adquate data structure here, array, object, etc)
4. c) correct answer(I would use a number for this)
5. create a couple of queestions using the constructor
6. store them all inside an array
7. select one random question and log it on the console, together with the possible answers(each question shpuld have a number) (Hint: write a method for the question objects to this task)
8. use the prompt function to ask the user for the correct answer. the user should input the number  of the correct answer such as you displayed it on Task 4
9. check if the answer is correct and print to the console whether the answer is correct or not(hint: write another method for this)
10. suppose this code would be a plugin for other programmers to use in their code.so make sure that all your code is private and doesn't interfere with other programer's code(hint: we learned a special technique to exactly that.)


----- Expert level ---

aftee you display the result, display the next random question, so that game never ends( hint: write a function for this and call it right after displaying the result)

be careful: after Task previous task, the game literally never ends. so include the option to quit the game if the user writes exit instead of the number. In this case, DON'T call the function from previous task 

tract thee user's score to make the game more fun! so eah time an answer is correct, add 1 point the score (hint: I'm goint to use the power of closures for this, but you dont have to, just do this with the tools you feel more comfortable at this point).
display the score i n the console. Use yet another method for this.