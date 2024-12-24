# Brainfuck
I don't like this name, but here you can find some brainfuck programs that i made or currently making.

# **Hello!** This is a very easy tutorial to know how to print characters in Brainfuck.

## So firstly, you have to understand the Brainfuck "symbols".

 - ">" moving pointer to the right
 - "<" moving pointer to the left
 - "+" increasing the block (byte) by 1
 - "-" decreasing the block (byte) by 1
 - "[" start of a loop
 - "]" end of a loop
 - "." printing out the ASCII decimal nr. 
 - "," it does something but right now I 
   didn't used it

The loop is going until somewhere in the loop hits zerus (0).

# So Dear "Kuncsaft" if you're already memorized those, I think we can start.

> I know that some people can do it shorter, but I think this method is more understandable.

Firstly, I think we should print a "Hello". It's going to look like this:

```
>+++++++[>++++++++++<-]>++.
>++++++++++[>++++++++++<-]>+.
>+++++++++++[>++++++++++<-]>--.
>+++++++++++[>++++++++++<-]>--.
>++++++++++[>+++++++++++<-]>+.
```
Let's break it down.:
>7+ - moves to the 2nd byte and increasing it's value to 7
[>10+<-] - starts a loop; moves to 3rd byte, adds 10 to it, goes back to 2nd byte and decreases by 1, and it does it until the 2nd byte hits 0.
>++. - moves to 3rd byte adds 2, and outputs.

It's like multiplication:
7*10=70
70+2=72=H

I think if you have time to experiment with it, you can learn the basics very quickly.

Some useful links:
- For ASCII code
https://www.ascii-code.com/  ~
- For interpreting BF:
https://sange.fi/esoteric/brainfuck/impl/interp/i.html
- A more useful, complete guide for Brainfuck:
https://gist.github.com/roachhd/dce54bec8ba55fb17d3a