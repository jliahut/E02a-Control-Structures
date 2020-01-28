Each of the python files is running a code asking What is its fovorite color. The right answer is red, and it varies as each python file updates and becomes more complicating.


- Open main01.py. Before running it, what do you expect this program to do?

It will display "Greetings!" on the next line. It displays "What is my favorite color?" on the following line, and whatever is entered will be the input. 


  - Now right click on the main1.py window and select “Run Python File in Terminal”. Click in the bottom panel, and answer the question. Describe what happened.
  
Greetings!
What is my favorite color?


  - What do you think the program did with what you typed in answer to the question? 
  
It saved it as an input substitute
  
  
- Open main02.py. Before running it, describe how this is different than main01.py.

main01.py will only save the input. main02.py will display the input on the next line.


  - What do you think the color = input() will do?
  
  color=input() will display what's inside the parenthesis, and it will save the string entered as color
  
  
  - Run the program in the terenttminal and answer the question. Did the program do what you expected?

Yes
  
  
- Open main03.py. Before running it, describe how this is different than main02.py.

They print the same thing until something is entered. If Red is entered, it will print Correct. It will print Sorry, try again. to anything else that is entered.


  - What is happening on lines 9–12?
  
It's an if-else statement. if-else statements are used as a boolean function.


  - Why are lines 10 and 12 indented?
 
 It is used to format the lines. Typically those lines are indented to keep everything organzied.
 
 
  - Run the program and answer the question. What happens if you don’t capitalize Red?
  
  Python will print Sorry, try again.
  
  
  - What does this tell you about "color"?
  
  color is case sensitive.
  
  
- Open main04.py. Before running it, describe how this is different than main03.py.

When python is running, it will take Run or run as an input.


  - What problem is this trying to solve?
  
It will take red as an answer. Red and red are the same thing in the real world. It's the same color.


  - Run the program and answer the question. What happens if you use some other capitalization scheme (i.e., “RED” or “reD“)?
  
It will print out Sorry, try again.


- Open main05.py. What do you expect line 9 to do?

The input for color will be lower-cased and if color is red it will print out Correct!


Line 9 is 'if (color.lower() == 'red'):'
  - What problem is it trying to solve?
  
  If color is the word red
  
  
  - Run the program and answer the question. What happens if you add spaces before or after the word (i.e., “ RED “ or “ red”)?
  
  Python will print out Sorry, try again. 
  
  
 - Open main06.py. How is line 9 different than in main05.py?
 
 main06.py has strip() in line 9.
 
 
   - What would you guess .strip() is doing?
   
   I looked it up. It strips away any spaces before or after the word
   
   
   - Run the program and answer the question. Is there another way of writing “red” that will break this logic?
   
   Yes. If I type r e d, it will be incorrect.
   
   
 - Open main07.py. Before running this program, how do you expect this to be different than main06.py?
 
 If someone types pink on main07.py, Python will return Close! on the next line
 
 
   - What is happening on line 12?
   
   Line 12 is elif (color=='pink'):. This is a else if statement. If pink is entered, it will print Close!
   
   
 - Open main08.py. What is the purpose of line 9?
 
 While color does not equal red, it will run a loop What is my favorite color until it is answered right.
 
 
   - Why are lines 10–17 indented?
   
 They follow the while statement.
   
   
   - Run the program. What would happen if line 10 were moved before line 9 (and no longer indented)?
   
The program will run forever saying Sorry, try again.


 - Open main09.py. What is happening on line 13?
 
 count=count+1 is on line 13. This means that the number will add one to itself after the loop restarts.
 
 
   - What is the purpose of “count”?
   
 It counts how many times it took you to guess the right color.
   
   
   - What is happening on line 22?
   
 It will print the number of time it took you to guess it right.


 - *Extra credit:* open main10.py. Add a comment to each line describing what it is doing (a comment follows a pound sign [#]).
 
 - *Extra credit:* open main11.py. What is happening on lines 6-11?
  
Commit your changes and push them back to the repository.
