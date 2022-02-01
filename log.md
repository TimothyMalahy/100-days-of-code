# 100 Days Of Code - Log

_____

### Day 0: January 23, 2022
#### Part 1

**Today's Progress:** Started Introduction to computer science and programming using python for the upteenth time.

**Thoughts:** I've started this a number of times. I'm hoping I can actually follow through especially if its only an hour a day.

**Anything I learned:** I learned again for the second time about imperative and declarative knowledge. Imperative is programattic, a process to figure things out. Declarative is factual. It is or it is not.

**Link to work:** [Calculator App](http://www.example.com)

**Links to study/review:** [MIT 6001](https://learning.edx.org/course/course-v1:MITx+6.00.1x_11+1T2017/block-v1:MITx+6.00.1x_11+1T2017+type@sequential+block@221a4c17dba341d6a970a0d80343253c/block-v1:MITx+6.00.1x_11+1T2017+type@vertical+block@b5c165683a074970946946a069a081b2)


_____

### Day 0: January 23, 2022
#### Part 2

**Today's Progress:** Continued through [MITX video: machines](https://learning.edx.org/course/course-v1:MITx+6.00.1x_11+1T2017/block-v1:MITx+6.00.1x_11+1T2017+type@sequential+block@221a4c17dba341d6a970a0d80343253c/block-v1:MITx+6.00.1x_11+1T2017+type@vertical+block@132cee3addc64d0fb5724b0df7af401b)

**Thoughts:** This stuff is the finer details of the programs and how it works. It's a high level perspective that I've skipped over historically.

**Anything I learned:** Fixed program computers are calculate distinct things, precisely one computation, stored program computers are machine stores and execute instructions whatever they may be in. Interpreters are in the computer and will walk through each sequence of the instructions and do the computations.

Basic Machine Architecture
- Memory
- Arithmetic Logic Unit (ALU) - takes memory as an input and then does primitive operations (Turing complete type things?) and then stores things up into memory again.
- Control Unit which contains Program counter - It keeps track of which specific operation you want to do at each moment. Like how assembly goes through each step. 
  - It points the computer to the next instruction to execute in the program

You don't want to just write things in terms of addition, subtraction, logical tests. You want to *abstract it* - Treat the square root as if the manufacturer made your computer as a primitive. Basically, you could run it on any machine.

**Link to work:** 

**Links to study/review:** 

**Questions to peruse/ask:** 
1. Is the ALU's primitive operations turing complete operations? 
   1. This was actually answered around [6:30](https://learning.edx.org/course/course-v1:MITx+6.00.1x_11+1T2017/block-v1:MITx+6.00.1x_11+1T2017+type@sequential+block@221a4c17dba341d6a970a0d80343253c/block-v1:MITx+6.00.1x_11+1T2017+type@vertical+block@132cee3addc64d0fb5724b0df7af401b) 
2. Is the Control Unit interpreting it at the assembly level?

_____

### Day 0: January 23, 2022
#### Part 3

**Today's Progress:** Continued through [MITX video: languages](https://learning.edx.org/course/course-v1:MITx+6.00.1x_11+1T2017/block-v1:MITx+6.00.1x_11+1T2017+type@sequential+block@221a4c17dba341d6a970a0d80343253c/block-v1:MITx+6.00.1x_11+1T2017+type@vertical+block@42476f76cf2245aaad39d1b1cd9bc027)

**Thoughts:** I like how when describing syntax, you can say a bunch of english words, but it doesn't mean its valid. i.e. "Cat dog boy" that's not syntactically valid. "Cat hugs boy" is syntactically valid. Much like "hi"5 won't output anything in python. It is a string and a number, but it doesn't interpret.

**Anything I learned:** 
- expressions - A complex, but legal combinations of primitives in a programming language.
- Primitive Constructs
  - example: English: words
  - akin to english and words, Programming language: numbers, strings, simple operators

static semantics: Which syntactically valid strings have a meaning - "I are hungry" is syntactically valid, but semantically it does not make sense. Noun, Verb, and adjective. Akin to python 3+"hi" That is a number and a string, but it doesn't work

Semantics: The meaning associated with a syntactically correct string of symbols with no static semantic errors. 

- Error types
  - Syntactic errors | Not written a legal expression. print('test) <-- Will not run
  - Static Semantic errors | Things are in the right order, but don't make sense. This will stop the program from running
  - No semantic errors, but different meaning than what programmer intended
    - Program crashes, stops running
    - program runs forever
    - program gives an answer but different than expected

**Questions to peruse/ask:**  Can I find more examples of static semantics and semantics?

_____

### Day 0: January 23, 2022
#### Part 4

**Today's Progress:** Continued through [MITx Video: Types](https://learning.edx.org/course/course-v1:MITx+6.00.1x_11+1T2017/block-v1:MITx+6.00.1x_11+1T2017+type@sequential+block@221a4c17dba341d6a970a0d80343253c/block-v1:MITx+6.00.1x_11+1T2017+type@vertical+block@799cb9ca20b4420a8f9ca116370179cd)

**Thoughts:**

**Anything I learned:** 
Objects are in two groups
- Scalar (Cannot be subdivided) - In python, integers, floats, bool, NoneType
- Non-scalar (have internal structures that can be accessed)

print (3+2) has no output and 3+2 has an output. Print returns NoneType and just logs it to the console.

double slash will remove the decimal, basically return an int not a float.

**Link to work:** 

**Links to study/review:** 

**Questions to peruse/ask:** 


_____

### Day 0: January 23, 2022
#### Part 5

**Today's Progress:** Continued through [MITx Video: variables](https://learning.edx.org/course/course-v1:MITx+6.00.1x_11+1T2017/block-v1:MITx+6.00.1x_11+1T2017+type@sequential+block@221a4c17dba341d6a970a0d80343253c/block-v1:MITx+6.00.1x_11+1T2017+type@vertical+block@458bc5cbbb06467ba62ad9146345a4f7)

**Thoughts:**

**Anything I learned:** Incrementing can be 'variable += 1'
You can re-bind variables. The value is still stored in memory, but lost the handle for it. 

**Link to work:** 

**Links to study/review:** 

**Questions to peruse/ask:** If you knew the address of the value, can you call that value back out without the handle?

______


### Day 0: January 23, 2022
#### Part 6

**Today's Progress:** Continued through [MITx Video: operators and branching](https://learning.edx.org/course/course-v1:MITx+6.00.1x_11+1T2017/block-v1:MITx+6.00.1x_11+1T2017+type@sequential+block@221a4c17dba341d6a970a0d80343253c/block-v1:MITx+6.00.1x_11+1T2017+type@vertical+block@3655b06b1b2f41528cfeecf3a272b8f8)

**Thoughts:** This was some real basics. It's almost as if the details of this video were complex enough that you had to actively think about it, versus the other ones were so simple you just know it as fact. However, it's only when you really think about those earlier ones do you truly understand it.

**Anything I learned:** Not equal is sometimes called 'bang equal'
5*2 == 5.0 * 2.0 resolves to True. Even though it's a float and an int, they still return True.

**Link to work:**

**Links to study/review:**

**Questions to peruse/ask:**

_____


### Day 0: January 23, 2022
#### Part 7

**Today's Progress:** Continued through [MITx Video: bindings](https://learning.edx.org/course/course-v1:MITx+6.00.1x_11+1T2017/block-v1:MITx+6.00.1x_11+1T2017+type@sequential+block@35f82f6c3ecb4e9e913dc279a9b73a9f/block-v1:MITx+6.00.1x_11+1T2017+type@vertical+block@c49275e36ae54e8eba9794af9ea60c9a)

**Thoughts:** This is more of a review video and if I did it separately I could see it being more relevant, but I've already done this stuff and I JUST finished it too.

**Anything I learned:** If you need to swap variables in code, you should make a temporary variable equal to the value so you can reset it. When you lose a binding name you cannot get it back.

**Link to work:**

**Links to study/review:**

**Questions to peruse/ask:**

_____

### Day 0: January 23, 2022
#### Part 8

**Today's Progress:** Continued through [MITx Video: strings](https://learning.edx.org/course/course-v1:MITx+6.00.1x_11+1T2017/block-v1:MITx+6.00.1x_11+1T2017+type@sequential+block@35f82f6c3ecb4e9e913dc279a9b73a9f/block-v1:MITx+6.00.1x_11+1T2017+type@vertical+block@86f3466af72b4a048fdaad54306b0d32)

**Thoughts:** 

**Anything I learned:** 'eric'[:] is a copy of the string, it's not the original but a copy.
'helloworld'[::-1], do the whole thing, to the last thing (because both sides of first colon are None), then do it backwards, because the last argument is steps and -1 is go through each step backwards.

**Link to work:**

**Links to study/review:**

**Questions to peruse/ask:**


_____

### Day 0: January 23, 2022
#### Part 9

**Today's Progress:** Continued through [MITx Video: input/output](https://learning.edx.org/course/course-v1:MITx+6.00.1x_11+1T2017/block-v1:MITx+6.00.1x_11+1T2017+type@sequential+block@35f82f6c3ecb4e9e913dc279a9b73a9f/block-v1:MITx+6.00.1x_11+1T2017+type@vertical+block@5f53323c35e74c259574cd0a91f43a81)

**Thoughts:** 

**Anything I learned:** Input expects everything to be a string. If I wanted to change it I would probably do a loop where I would check if the type is an int or something. Then I would continue to asking input, but I'd have to cast it.

**Link to work:**

**Links to study/review:**

**Questions to peruse/ask:**


_____

### Day 0: January 23, 2022
#### Part 10

**Today's Progress:** Continued through [MITx Video: control flow](https://learning.edx.org/course/course-v1:MITx+6.00.1x_11+1T2017/block-v1:MITx+6.00.1x_11+1T2017+type@sequential+block@35f82f6c3ecb4e9e913dc279a9b73a9f/block-v1:MITx+6.00.1x_11+1T2017+type@vertical+block@f25f8b4ed0be483e9fb70b5f39ad0f50)

**Thoughts:** I skipped over the IDE video as I believe they use spyder and ipython, but I am familiar enough with VS code and comfortable with environments that I'm not overly worried.

Iterating over a loop and the num +=2 was difficult to predict the output  because it kept performing it and THEN exiting the loop therefore making it iterate up 1 more than I thought of.

**Anything I learned:** 

**Link to work:**

**Links to study/review:**

**Questions to peruse/ask:**


_____

### Day 0: January 23, 2022
#### Part 11

**Today's Progress:** Continued through [MITx Video: Iteration](https://learning.edx.org/course/course-v1:MITx+6.00.1x_11+1T2017/block-v1:MITx+6.00.1x_11+1T2017+type@sequential+block@35f82f6c3ecb4e9e913dc279a9b73a9f/block-v1:MITx+6.00.1x_11+1T2017+type@vertical+block@d7d6757649674d829be5baebea57adcb)

**Thoughts:** For loops are not as easy as they seem at times. I'm curious if someone like Kevin could do better with these challenges or if it would take him thinking as hard as I did

**Anything I learned:** 

**Link to work:**

**Links to study/review:**

**Questions to peruse/ask:**



_____

### Day 0: January 23, 2022
#### Part 12

**Today's Progress:** Continued through [MITx Video: Guess and Check]()

**Thoughts:** I don't have a lot of thoughts. Honestly just running out of steam for the day. Probably gonna take a nap and go at it later. I've spent 2 to 3 hours today.

**Anything I learned:** 

**Link to work:**

**Links to study/review:**

**Questions to peruse/ask:**



_____


### Day 1: January 24, 2022
I didn't do anything today. Which is a bummer, but I was hanging out with Jaylin and his friends and chatting.


### Day 2: January 25, 2022.

**Today's Progress:** Today I restarted CS50. I skipped around, but it was enjoyable to rewatch.
I finished hello program for cs50 week 1, but now I still have to watch the video and do mario and cash.

**Thoughts:** I was also blown away by the CS50 video player

**Anything I learned:** I learned about github codespaces, which seems like an absoultely killer process.

**Link to work:**

**Links to study/review:**

**Questions to peruse/ask:**


### Day 3: January 26, 2022

**today's progress** continued a bit of CS50 started the mario less comfortable and started to work through the loops and get the variables queued up. Utilizing debug50... Looking forward to python parts :)


### Day 5: January 28, 2022

**today's progress:** it's 3 AM and I just spent 40 minutes or so on CS50x's mario less comfortable. I think I definitely need to just do this in the morning since I have a horrible sleep cycle and when I get to work I don't work on my own personal things. It's better to just do it at home I think.

### Day 6: January 29, 2022

**today's progress:** It's 5:30 AM. I'm going to watch a bit of CS50 lecture, but I also contributed to a tkinter program for a calculator which was a nice warm up to the day. Helped out a bit on reddit comments related to django and pandas.

**thoughts:** Today was good. I was a bit stressed this morning and frustrated with the dog and animals, but programming helped me forget about some of those.

**Links to work:** [Calculator (mine) PR](https://github.com/TimothyMalahy/Fluent-Python-Calculator/tree/main)

[Calculator source repo](https://github.com/HuyHung1408/Fluent-Python-Calculator)

**Anything I learned:** 

Week 2 of CS50 covers the arrays, but it also showed how the make function is implementing the clang function (C lang) and how it defaults to produce an a.out, but then clang -o hello hello.c will make a file called "hello"

"linker command" is an error because the compiler doesn't know about the get_string function. So you add in a new argument. 
> clang -o hello hello.c -lcs50
This links in the cs50 that is included into the main function.

> make is an automation of the clang command

When you compile your code, your computer is doing 4 things.
1. Preprocessing code --> This is the #include <cs50.h> --> This is telling the compiler to find the files on the harddrive and teaching the compiler about the string, exactly like the prototype of the function, except its a whole file
2. compiling code --> Convert the code to assembly language
3. assembling code --> Converts the assembly language into machine code which is 0s and 1s
4. linking code --> Links all the prepocessed, compiled, assembled, packages into 1 singular file which is called "a.out" or "hello"


### Day 7: January 30, 2022

**today's progress:** did some CS50 in the middle of the day.

**Anything I learned:** Null is a sentinel character and it helps delineate where one string ends and the next one begins. You use the symbol "\0" which is 8 "0" bits, or one byte full of 0 bits. So to store a word like "Hi!" uses 4 bytes. H, I, !, and "nul"
In C you can see the char-array with printing more characters than it has. For example
> string s ="HI!";
> printf("%i %i %i %i\n", s[0], s[1], s[2], s[3]);

This outputs "72, 73, 33, 0" <-- ascii number of the characters and null character...

the 'void' in int main(void) is the way to tell the computer that the programs we've written do not take command line arguments.

int main(int argc, str argv[])
- argc is the count of how many words there are as an int
- the argv will make an array of all the arguments

For error catching and exiting the program, you should return a non-zero value.
If it does work you should return 0.
- main function is already doing this automatically.

### Day 8: January 31, 2022

**today's progress:** finished CS50's substitution for week 2. Kicked my ass, but it was very rewarding.

**Anything I learned:** I learned about segmentation faults related to C arguments. I also learned about a way to continuously add characters to arrays, which could be used to compare against the ciphered array.