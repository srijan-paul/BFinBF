# Brainfuck interpreter in brainfuck.

This is a very simple (and a bit unoptimized) brainfuck interpreter written
in brainfuck.

# Try it out

To run your code using this interpreter, go to [this](https://copy.sh/brainfuck/) online 
brainfuck interpreter (because you still need a brainfuck interpreter to run the interpreter)

Then, copy paste the contents of `bf_interpreter.bf` to the codesection of that site.

Write your own brainfuck code in the input section, and hit run :) 

# How ? 

By cheating. I first wrote a language that compiles to brainfuck [here](https://github.com/srijan-paul/meep)
and then wrote a brainfuck interpreter in that language. Finally I compiled the interpreter.

# Limitations

Under a 1 byte per cell memory tapem It can't run code larger than 256 characters,
however, with slight modification to the [original](https://github.com/srijan-paul/meep/blob/main/test/bfinterpreter.meep)
code, this is entirely possible, but will slow it down by a lot.

Another solution is to just use an interpreter with a memory cell size of 16 bits or higher (which you can do in copy.sh)
