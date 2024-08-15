# HACK-Assembly-Journey

The HACK assembly language is an interesting language I learned at the University of the People. 

Here, each file translates the code below it into the equivalent HACK assembly language.
- *for_loop.asm*
```console
j = 5
for(i = 1; i < 5; i++) {
  j--
}
```
- *if_then_else.asm*
```console
i = 4
if (i < 5) then
  j = 3
else
  j = 2
```
- *while_loop.asm*
```console
i = 0
j = 0
while(i == 0) {
  j++
  if j == 5 then
    i = j
}
```
- *array_traversal.asm*
```console
A[0] = 5
A[1] = 4
A[2] = 3
A[3] = 2
A[4] = 1
A[5] = 0
for (i = 0; i <= 5; i++) {
  if A[i] == 0 then
    A[i] = 5;
}
```
- *bubble_sort_algorithm.asm*
```console
// Bubble Sort Algorithm in Pseudocode
A[0] = 5
A[1] = 4
A[2] = 3
A[3] = 2
A[4] = 1
A[5] = 0
int j;
flag = 1;    // set flag to true to begin first pass
int temp;    // holding variable
while (flag == 1)
{
  flag= false;		        // set flag to false awaiting a possible swap
  for ( j = 0 ;  j < 6 ;  j++ )
  {
    if (A[ j ] > A[j+1] )	// test for ascending sort
    {
      temp = A[ j ];      // swap elements
      A[ j ] = A[ j+1 ];
      A[ j+1 ] = temp;
      flag = 1;		        // shows a swap occurred 
    }
  }
}
```


To run these *.asm* files, you need `the HACK Assembler` which is in the [nand2tetris/tools](https://drive.google.com/file/d/1xZzcMIUETv3u3sdpM_oTJSTetpVee3KZ/view).
I recommend reading this [manual](https://drive.google.com/file/d/1IkIR8Pwq3PY49QgXpUJOkUUVht-TKIET/view) for setup before downloading anything.

You can also find useful programs like compiler, emulator, simulator, and others.
These tools are provided by the [Nand to Tetris](https://www.nand2tetris.org/) platform.
