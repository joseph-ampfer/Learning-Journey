# Learning-Journey
See how far I've come, from med student to software engineer.

## My Journey Through Harvard's CS50

### Week 0: Scratch
- **Topics Learned:**
  - Introduction to the basics of computer science
  - Understanding algorithms
  - Creating simple programs using Scratch

- **Problem Set:**
  - Design and implement a simple animation, game, or interactive art using Scratch
 
- **My Games**
  - https://github.com/joseph-ampfer/Jumpy-Game
  - https://github.com/joseph-ampfer/My-Pong

- **Reflections and Challenges:**
  - I loved working on my games. The thrill of seeing something you imagined and coded actually working was amazing. I knew then that I wanted to dive deeper into software engineering.
  - I got stuck on how to get the physics right on pong. I was thinking of having the incoming angle of the ball and outgoing angle be correct. After thinking it over, searching formulas, and trying implemenations that did not work, I had an aha moment that I could set the angle to be random within a certain interval, and the game would still be fun. I found the randomness of the angle added to the fun of the game, because it was harder to predict.

### Week 1: C
- **Topics Learned:**
  - Introduction to the C programming language
  - Basics of programming concepts like loops, conditions, and variables

- **Problem Set:**
  - Implement programs in C, "Hello, World", a simple or complex Mario pyramid, and a cash change calculator

- **Reflections and Challenges:**
  - Transitioning to C from Scratch
  - Understanding new programming concepts in C
  - I tried to tackle the complex Mario pyramid first and found it a little overwhelming, so I went back to simple pyramid. From there, I found out that I could make the backwards pyramid pretty easily, and from there get the solution. Once I had that solution, the complex Mario pyramid came easily.
  - I learned that breaking a hard problem down to a smaller and easier to understand base can simplify the whole process.

### Week 2: Arrays
- **Topics learned:**
  - Compiling: preprocessing, compiling, assembling, and linking
  - Debugging: Techniques like using `printf`, utilizing debugger tools, and rubber duck debugging
  - Arrays: Introduction to arrays and how they store data in contiguous memory locations
  - Strings as Arrays: Understanding that strings are arrays of characters
  - Command-Line Arguments: How to handle arguents passed to programs via the command line.
  - Basics of cryptography

- **Problem Set:**
  - Implement programs that manipulate arrays of data

- **Reflections and Challenges:**
  - Grasping array manipulation
  - I got to see the value of different debugging techniques and their practical applications
  - Worked on a Ceasar cipher and substitution cipher in C, which was fun to play with
  - I created a Wordle game that runs in the terminal. It took a lot of effort, and troubleshooting to have it check if the letters were in the word but in the wrong spot, but this was again one of those amazing momoments of coding. I was so excited to show the game to my roommates, have them play it, and have it work flawlessly. It is a great feeling.

### Week 3: Algorithms
- **Topics Learned:**
  - Delving deeper into algorithms
  - Binary Search
  - Running time and algorithm efficiency
  - Data structures
  - Sorting Algorithms: Explored selection sort, bubble sort, and merge sort
  - Recursion understanding and implementation

- **Problem Set:**
  - Implement programs that execute more complex algorithms, like search algorithms and election tally algorithms.

- **Reflections and Challenges:**
  - Understanding efficiency in algorithms
  - It was cool to see the efficiencies of the sorting algorithms live with the problem sets. It took theory and showed practical use.
  - Recursion was tricky, and I spent a lot of time thinking through the logic of how it was working.
  - I ran into Tideman when working on extra problems. It was really tough, and I didn't realize that if I had the knowledge of pointers from Week 4, it would have been so much simpler.

### Week 4: Memory
- **Topics Covered:**
  - Memory management
  - Pointers and file I/O
  - Valgrind for detecting memory leaks
  - Overflow errors from the heap or stack

- **Problem Set:**
  - Programs that manipulate memory and use pointers

- **Reflections and Challenges:**
  - Understanding pointers and memory allocation
  - Debugging memory-related issues
  - Pointers were very interesting to learn and use because how powerful they are with memory manipulation. It made me realize what C could do.
  - I made custom filters in C that would take an image and process each pixel and output an image that is 'filtered'. It was fun to my code work and output different filters that I have seen used on social media!
  - Learning about memory and garbage values allowed me to create a program than can recover deleted files from a camera, which was very cool. I felt like a detective recovering lost evidence.

### Week 5: Data Structures
- **Topics Learned:**
  - Abstract data structures like stacks and queues
  - Resizing arrays dynamically using 'malloc' and 'realloc'
  - Linked Lists and how to dynamically grow and shrink them
  - Trees and Binary Search Trees
  - Dictionaries and Hashing
  - Tries

- **Problem Set:**
  - Implementation of data structures in program solutions

- **Reflections and Challenges:**
  - Understanding and implementing various data structures
  - Application of data structures to solve complex problems
  - This week was extra interesting because the problem set not only wanted us to make an accurate spell checker, but also optimize it. I had to make it run as fast as I could, and that got my brain going. It was the speed of the hash function (no outside hash functions allowed) that was the linch-pin for my speed, and it was satisfying to get it to about the same speed as the professor.

### Week 6: Python
- **Topics Learned:**
  - Transition from C to Python
  - Python syntax and features
  - Object-oriented programming

- **Problem Set:**
  - Implement similar programs from earlier weeks in Python

- **Reflections and Challenges:**
  - Adapting to Python from C
  - Leveraging Python features in problem-solving
  - This was a big transition, and opposed to many of my classmates, did not like Python at first. I thought it was not as pretty as C, and hated how non-explicit everything was. In C, I had loops down-pat. I wanted to know exactly what was going on under the hood for all these Python functions, like it's 'for'. Instead of taking it at face value, it led me into a deep dive of what these abstractions were doing behind the scenes. I did come to enjoy the relative ease I could do certain things in Python as compared to C.

### Week 7: SQL
- **Topics Learned:**
  - Database management using SQL
  - Querying and updating databases
  - Using SQL in Python
  - Race Conditions
  - SQL Injection Attacks

- **Problem Set:**
  - Implement programs that interact with databases using SQL

- **Reflections and Challenges:**
  - Understanding database concepts
  - SQL syntax and query optimization
  - I loved this week. Working with SQL and databases came very natural, and the problems were fun. The Fiftyville problem had me feeling like a real criminal investigator like Penelope Garcia from 'Criminal Minds'. 

### Week 8: HTML, CSS, JavaScript
- **Topics Learned:**
  - Introduction to web development
  - Understanding HTML, CSS, and JavaScript

- **Problem Set:**
  - Develop a simple web page or application using HTML, CSS, and JavaScript

- **Reflections and Challenges:**
  - Designing and implementing web interfaces
  - Integrating JavaScript for web functionality
  - This was the hardest week for me. Transitioning from C to Python wasn't bad, but from those to HTML, CSS, and JavaScript shook me up. I thought HTML and CSS looked ugly, did not like how it seemed like memorization, not logic coding, and how arbitrary and deep the look of a page can be. There was a lot I wanted to with my webpage, and felt like there wasn't adequate instruction. Once I got over my self-restriction of not using outside resources, it became more clear how to create what I envisioned.

### Week 9: Flask
- **Topics Learned:**
  - Introduction to Flask
  - Building dynamic websites

- **Problem Set:**
  - Implement a more complex web application using Flask

- **Reflections and Challenges:**
  - Understanding web application frameworks
  - Managing server-side scripting
  - I made a Flask web application, which was cool because it was my first full-stack experience. I made a database, a Flask application, and the front-end HTML and CSS. I ended up adding a lot of additional functionality that was not necessary for the grade, but I did it because the challenge was fun, rewarding, and it made for a more complete product in my opinion.

### Week 10: Final Project
- Worked on my final project, AMPFER Finance
- https://github.com/joseph-ampfer/AmpferFinance
