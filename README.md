
# SNHU - CS350 Emerging Systems and Architecture

### Summarize the project and what problem is was solving.

* For GPIOMorseCode project, the project was to utilize callbacks, interrupts, and timers using GPIO.
This means I had to utilize callbacks for each GPIO and based on those callbacks would change a state value, thus allowing the state to be changed.
Whether the state was SOS_State or OK_State meant that it would call a pattern in morse code switching the onboard lights on or off.

### What did you do particularly well?
* I was particularly well with articulating my state machine and the different states, along with generating an efficient method for switching the lights
on and off in morse code. I think developing a function for each state and calling that function within each state allowed for each function to run and at the same time capture user input.
This allowed for input to be captured, as well as the independent states to operate normally.

### Where could you improve?
* I think I could improve in my clarity and organization of the code (as I think this would come with time and experience)
I think my organizational skills for my code was a bit disorganized and think I could've been more intuitive with DRY principles.

### What tools and/or resources are you adding to your support network?
* Tools I will adding to my support network include Code Composer Studio, TI documentation and experience, understanding embedded systems terminologies.
Learning about various aspects of embedded systems such as the compiler, and C language specific to embedded systems.

### What skills from this project will be particularly transferable to other projects and/or course work?
* I think problem solving skills, testing, and learning flow of applications will be very useful. These skills are applicable in all aspects of software engineering.
I also think the embedded systems concepts such as GPIO, UART, I2C and the various components on a board have helped massively. Understanding memory and different formats and types have been especially useful.

### How did you make this project maintainable, readable, and adaptable?
* I made the project maintainable by creating the proper functions, states using switch cases, and while loops when necessary. I also made it readable by creating proper spacing, variable names, and documentation where necessary.
I made the project adaptable by creating easily understandable code for functions and state machines.