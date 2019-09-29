# CPE 1040 - Introduction to Computer Engeneering

## Assignment: Migrating micro:bit Programming from Blocks to JavaScript

### 1. Summary

This assignment asks you to go through a [Intro to CS course with Blocks](https://makecode.microbit.org/courses/csintro) for the micro:bit, and write parallel programs using the JavaScript equivalent of the code in the course modules. This assignment is submitted through Github.

### 2. Requirements

#### 2.1 Section programs

1. The CS course is broken down into thematic sections. There are 5 sections + 1 midterm project + 5 sections + final project. Each section has 4 parts. You want the _Activity_ part, which contains the section's CS material and Blocks.

2. You need to write a _working_ JavaScript (JS) program for the micro:bit for each of these sections/projects, for a total of 12.  

3. For the non-project sections, you are required to use the JS equivalent of the material from the section. _**Note:** For these programs, you are allowed to look at the JS translation of Blocks programs._

4. For the midterm project, you are required to use the JS equivalent of the material from all 5 preceding sections.  _**Note:** For this project, you are NOT allowed to look at the JS translation of Blocks programs._ (An aside: if you don't know how to read a statement like "you are not allowed to", the intended and preferred interpretation is "you can do whatever you want and won't be penalized by me, but, if you want to learn most effectively, I suggest that you do not resort to...".)

5. For the final project, you are required to use the JS equivalent of the material from all 10 preceding non-project sections. _**Note:** For this project, you are NOT allowed to look at the JS translation of Blocks programs._

#### 2.2 Github commits & tags

1. Working in the Makecode browser environment, you cannot save the JS file of your program in a directory of your choosing. It is stored in an in-browser memory object and is not accessible. (A side note: there might be a Makecode app for Windows which might actually allow that, but there is nothing like that for Mac, to the best of knowledge.) So, you will need to copy the JS from Makecode to another editor (preferably, a code editor with syntax highlighting and code manipulation) and then save and commit it.

2. You need to commit the changes and additions to your assignment for each section or project. This means that there should be _at least_ 12 commits pushed to your remote assignment repository on Github when you are done. I advise you to have more than that, to get used to it.

2. You need to **tag** the final commit for each section. Tags are under _releases_ in the repository bar on the Github page of the assignment repository. The tag should be one of the following `v0.1`, `v0.2`, ..., `v0.12`, for each section, respectively. (Terminology clarification: the `git` command is `git tag`, but tags are counted as _releases_ on Github.)

3. You need to update the assignment repository [README.md](README.md) (this document, in the section [Tags](#tags)) with a short description of your section program or project, **before** you tag. You can do that directly on Github after you push your commits from your local repository.

#### 2.3 Project design

1. For each of the two projects, you need to include a design "document" in the [README.md](README.md) (this document, in the section [Designs](#designs)).

2. The design "document" should follow the _problem-solving tips_ in the [mini-project page](https://makecode.microbit.org/courses/csintro/miniproject).

3. The design "document" should have at least the following sections: Goal, Design process, and JS Language Constructs & Objects. Articulating clearly your engineering work is a key professional skill.

## Resources

### micro:bit 

1. [micro:bit lessons](https://makecode.microbit.org/lessons).

2. [micro:bit ideas](https://microbit.org/ideas/).

3. A list of some more [advanced projects](https://www.itpro.co.uk/desktop-hardware/26289/13-top-bbc-micro-bit-projects).

4. The [projects](https://www.itpro.co.uk/desktop-hardware/26289/13-top-bbc-micro-bit-projects) at the [awesome micro:bit list](https://github.com/carlosperate/awesome-microbit).

### Github

1. Github Tutorial for Beginners ([webpage](https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)).

2. Github Basics for Mac and Windows ([video](https://www.youtube.com/watch?v=0fKg7e37bQE)).

3. git & Github Crash Course for Beginners ([video](https://www.youtube.com/watch?v=SWYqp7iY_Tc)).

4. Introduction to Github for Beginners ([video](https://www.youtube.com/watch?v=fQLK8Ib_SKk)).

5. About `git` ([webpage](https://git-scm.com/about)).

6. `git` [documentation](https://git-scm.com/doc) (webpage, book, videos, reference manual).

### JavaScript

1. Technically, the language which is used side-by-side with Blocks in the Makecode environment is a subset of [TypeScript](https://makecode.com/language), which itself is a superset of JavaScript (technically, [ECMAScript](https://www.ecma-international.org/ecma-262/10.0/index.html#Title)), with some JS features not implemented in Makecode.

2. The limited [JavaScript mini-tutorial](https://makecode.microbit.org/javascript) in Makecode. Make sure you read it but that can't be your only reference.

3. Official [TypeScript documentation]():
   1. TypeScript in 5 min [tutorial](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html). _**Highly recommended!** You will need to [download](https://www.typescriptlang.org/index.html#download-links) and install an integrated development envinronment (IDE). The two that I recommend are Visual Studio Code from Microsoft and WebStorm from JetBrains._
   2. The full documentation and reference is under _Handbook_. Bear in mind that you are drinking from the hose. Don't be surprised if not everything is presented in a strictly incremental manner.
   
4. In-browser TypeScript [playground](https://www.typescriptlang.org/play/index.html). Note that micro:bit specific code will not run, but you can still play. _Start making the distinction between a generic multi-purpose programming language (TypeScript) and functionality (libraries, objects, etc.) that is specific to a particular device (micro:bit), though written in the same programming language._

5. A pretty good and very palatable JS tutorial with in-browser coding, by [Codecademy](https://www.codecademy.com/learn/introduction-to-javascript).

6. Extensive and detailed [JS tutorial](https://javascript.info/), with some advanced material thrown in. _**I like this one!**

7. The most authoritative JS resource on the Web, including tutorials and reference, by [Mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript).

---

## Tags

### v0.01

[First micro bit program](https://github.com/Introduction-to-Computer-Engineering/migrating-microbit-programming-from-blocks-to-javascript-O11WL1D/blob/master/micro%20pet%20program%2C%20project%20%231) 
Description:  micro_pet#1.js turns the bcc micro bit into a nervious shifty character who endlessly scans the room for witnesses
 

### v0.02

[Algorithms](https://github.com/Introduction-to-Computer-Engineering/migrating-microbit-programming-from-blocks-to-javascript-O11WL1D/blob/master/Algorithms%2C%20conditional%20face%20program%20%232)
Description : A program which depending on input from the a, b and ab buttons of the microbit, displays different variations of a smiling face and frowning
face. Press A for smile variation, B for frown variation, and AB for random variation.   
 

## v0.03
[Variables](https://github.com/Introduction-to-Computer-Engineering/migrating-microbit-programming-from-blocks-to-javascript-O11WL1D/blob/master/Varibles%20project%233%2C%20score%20keeper%20program)
Description: Scorekeeping program which records the score of two players + amount of ties. Press A to increment/display player one score, B to 
increment/display player 2 score, and AB to record/display ties   


## v0.04
[conditionals](https://github.com/Introduction-to-Computer-Engineering/migrating-microbit-programming-from-blocks-to-javascript-O11WL1D/blob/master/Project%204%2C%20rock%20paper%20scissors%2C%20conditionals)
Desciption: 2 player Game of rock paper scissors for micro-bit, on the program's start press the a and b buttons to cycle through player 1's
input and then press the AB button to switch to player 2. After player 2 repeats the same process, Press the ab button and either the a or 
b button to see the games result.

## v.05
[iteration](https://github.com/Introduction-to-Computer-Engineering/migrating-microbit-programming-from-blocks-to-javascript-O11WL1D/blob/master/Project%20%235%2C%20loops%2C%20traveling%20sprite%2C%20yeah)
Desciption: A program which utilizes looping to toggle each led of the micro bit row by row in a sequental manner.





## ------------------------------------ v.06 [Midterm project](https://github.com/Introduction-to-Computer-Engineering/migrating-microbit-programming-from-blocks-to-javascript-O11WL1D/blob/master/Midterm%20project%20code%2C%20program%20%236)----------------------


## Description:
The fitness gram pacer pal program serves to turn the bbc Mircobit into a supplementary tool
 for use in the nationally acclaimed fitness gram pacer test. The program acts as both a timer, and a score keeping 
device for the number of laps or levels achieved in the test. Pressing the A button after powering up the bbc Microbit
 will result in a timer to begin, which either displays the elapsed time in seconds or in minutes depending on the state 
of the AB button toggle. As the timer runs, its value is compared with the pacer test's various level benchmarks and when
 the duration requirements of any given level are fulfilled, the program’s score variables are updated. Pressing the B button
 will stop the timer and display the users score in laps. 



## Brainstorm

-8 bit gpio_controlled ram module 
(-pacer_test Stop watch 'with each iteration adds/displays new second')  <--- features all required aspects

## Goal
To create software for the bbc Microbit which both acts as both a scorekeeping device for the fitness gram pacer test
and as a timing device. 

## Design process
The first step in my design process was to set up the timing code which would keep track of the elapsed time in both minutes and
 seconds.To do so I created a loop which would increment a seconds variable, and some code which would add a second long delay 
between each iteration of the loop. Afterwards, to implement minutes I added a conditional which would check to see if seconds was 
equal to 60, and if so the minute counter would be incremented. with the foundation of the program established, I was able to then 
add a statement which evaluates the value of minutes and assigns the lap counter to a predicted amount of laps. Finally, I added an
 input conditional statement which stops the timer when the B button is pressed.

## Constructs
The fitness gram pacer pal program features the following constructs
-looping
-Variables
-Conditional statements
-Algorithms



## ----------------------------------------------------------------------------

## v.07
[coordinates](https://github.com/Introduction-to-Computer-Engineering/migrating-microbit-programming-from-blocks-to-javascript-O11WL1D/blob/master/coordinates%20program%20%237)
Description:  Utilizing the micro bit's led coordinate interface to randomly toggle each led and to make a smiley face.
The A button activates led randomization and the B button toggles a smiley face.


## v.08 
[booleans](https://github.com/Introduction-to-Computer-Engineering/migrating-microbit-programming-from-blocks-to-javascript-O11WL1D/blob/master/Coin%20flip%20bool%20comparison%20program%2C%20%238%20-!)
Description: A simple coin flip game which randomly generates two boolean values and compares them with each other. In the case of a tie, player 2 gains a point, and in the case of
different values, player 1 gains a point. 
The A button generates and compares the two boolean values, and returns the result of the comparasion. 
Pressing the AB button will display the two players scores.


## v.09
[Binary](https://github.com/Introduction-to-Computer-Engineering/migrating-microbit-programming-from-blocks-to-javascript-O11WL1D/blob/master/Decimal%20to%20binary%20converter%2C%20project%20%20%239)
Description: A program which converts user selected decimal values to binary, 
On start: press the A and B buttons to cycle through a value from 0 to 255,
To see binary equilivant starting from the least significant bit, press the AB button

## v.10
[radio](https://github.com/Introduction-to-Computer-Engineering/migrating-microbit-programming-from-blocks-to-javascript-O11WL1D/blob/master/Activity%20%2310%2C%20radio%2C%20micro%20bit%20project)
Description: -sends out radio packets to other micro bits, which upon recieving displays the contents of the recieved packet.
Press the A button to send out a packet containing the string "marco"  +random noise(not an error, I was getting bored)
Press the B button to send out a packet containing the string "polo" 

## v.11
[arrays](https://github.com/Introduction-to-Computer-Engineering/migrating-microbit-programming-from-blocks-to-javascript-O11WL1D/blob/master/Activity%20%2311%2C%20arrays%2C%20random%20name%20generator)
Description: -a name generator which randomly selects values in three name arrays and returns the result. 
press AB to display a random name 


## --------------------------------------------- V.12, [Final project](https://github.com/Introduction-to-Computer-Engineering/migrating-microbit-programming-from-blocks-to-javascript-O11WL1D/blob/master/Final%20project%2C%20memory--letter%20storage--transmission)---------------------
## Description:
The data array program stores ascii, decimal or binary values in an array of 25 elements, which are each individually
represented by the bbc's 25 leds. The program allows users to navigate, alter and view the values of each led/position as well as transmit
their contents to other microbits.

In operating mode 0 the user is able to navigate from one led or memory block to the other 
by using the A Button to go left and the B button to go right. Pressing both A and B will advance the toggled led/memory position to the 
next row. By shaking the Micro bit, the user is able to access operating mode 1, which if either the A or B button is pressed while active,
the microbit will show the ascii representation of the value stored in said position. Pressing AB once will display the decimal value, and pressing ab 
once more will show the binary representation of the value starting from the least significant bit. Shaking the micro bit again will take 
the user to operating mode 2, where the user is able to edit the value stored in the current position. Pressing the A and B buttons in the 
mode will cycle through all of the possible ascii values starting from 97 and ending in 127. When AB is pressed, the previously seen 
ascii value will be assigned to the current position. In mode 3, the User can transmit the value, the x coordinates and y coordinates of the
current led/memory position to other microbits via radio. Upon recieving radio packets, the intercepted value is assigned to the 
specifyied xy position. With one last shake, the user is brought back to operating mode #0

    


## Brainstorm:
-Gpio controlled memory module --> would need to use serial communication, and I really dont have time to learn how to do that
-wii type block memory- might work
---inspired by the wii game systems memory storage, as seen in the link https://www.youtube.com/watch?v=6W1a-PFPUJs
[Operating modes ideas](https://github.com/Introduction-to-Computer-Engineering/migrating-microbit-programming-from-blocks-to-javascript-O11WL1D/blob/master/IMG_20190928_222123175.jpg)
[Navigation system idea]()

## Goal:
To design and create software for the Bbc microbit which incorporates all of the concepts previously taught concepts and a led positioning system. 



## Design process
To lay the foundation for the rest of my program the first thing I made was the led/array navigation system. Javascript didn't feature multidemensional arrays, so 
to work around this I used a standard array of 25 items and used the following expression to partition each element into 5 rows of 5 : memory[(y*5)+x]. Afterwards, I started designing 
a system which allowed the user to select ascii values from 97-127, and implemented a feature that set the value of the current position to the users selected value. Unfortunately, this 
is where I began to have problems. Initally when I designed the program I made it so that each phase was nested in the execution block of the AB button. However since the a-b inputs of the
different phases suddenly started conflicting with each other, I decided that It would be best If I had only one input for each button and a conditional statement for each phase.
after that issue was fixed, I added a feature which would transmit the xy coordinates and the value of the current position, and some code which upon intercepting radio packets would
store each value in a array for later assignment. From there, I added the options to view each value in decimal, and in binary.  




## contructs:
Making, Algorithms, Variables,Conditionals,iteration,Coordinates,booleans,binary,Radio,arrays
## ---------------------------------------------------------------------

