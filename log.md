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

### Day 0: January 23, 2022
#### Part 13

**Today's Progress:** Continued through [MITx Video: ]()

**Thoughts:** 

**Anything I learned:** 

**Link to work:**

**Links to study/review:**

**Questions to peruse/ask:**