# Hello World! in Brainfuck

[See the result for yourself](https://copy.sh/brainfuck/?file=https://raw.githubusercontent.com/Fishezzz/Brainfuck_Hello-World/master/hello-world.b)

[Brainfuck on Wikipedia](https://en.wikipedia.org/wiki/Brainfuck)

Breakdown of the code:

```
++++ ++++
[
    >++++
    [
        >++
        >+++
        >+++
        >+++
        >+
        <<<<<-
    ]
    >+
    >+
    >-
    >+++
    >>+
    [<]
    <-
]

The result of this is:
Cell No :   0   1   2   3   4   5   6   7
Contents:   0   0  72 104  88 120  32   8
Pointer :   ^
 
>>.         #2  H  72
>---.       #3  e  101
+++++++.    #3  l  108
.           #3  l  108
+++.        #3  o  111
>>>.        #6     32
<<-.        #4  W  87
<.          #3  o  111
>>------.   #5  r  114
<<---.      #3  l  108
--------.   #3  d  100
>>>+.       #6  !  33
-.          #6     32
<<---.      #4  T  84
<++++.      #3  h  104
+.          #3  i  105
>>+.        #5  s  115
>.          #6     32
<<<<+.      #2  I  73
>>>.        #5  s  115
>.          #6     32
<<<<---.    #2  F  70
>.          #3  i  105
>>.         #5  s  115
<<-.        #3  h  104
>>+++++++.  #5  z  122
.           #5  z  122
.           #5  z  122
>+.         #6  !  33
>++         #7  \n 10
```
