[![64-bit xorshift RNG](xorshift64logo.png)](https://github.com/aelfimow/xorshift64-asm/blob/master/xorshift64logo.png)

# 64-bit xorshift random number generator functions (in x86 assembly language)

Implementation of 64-bit xorshift random number generator discovered by
George Marsaglia and described in his paper about Xorshift RNGs.

## src1
For 64-bit xorshift RNGs George Marsaglia proposed 275 triples, which are
used here in 275 assembly functions.

## src2
These assembly functions must be parameterized with a triple and differ from
the src1 functions this way, that a valid triple must be provided by the user.

# Note
The assembly files have been generated using my [cppasm](https://github.com/aelfimow/cppasm)
generator.
