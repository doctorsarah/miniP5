# program-chap05

Use the provided **URLDissector.java** as a starting point to create a **FractionReader**. Instead of reading URL's, read fractions from a file named **fractions.txt**, one per line, add them to an **ArrayList**, and print them in reverse order with their values.

## Expected Output
```
110/50 = 2.2
99/98 = 1.010204081632653
1/5 = 0.2
7/8 = 0.875
2/3 = 0.6666666666666666
5/6 = 0.8333333333333334
21/7 = 3.0
3/4 = 0.75
```
## Recommended Phases
1. Change names:
   * Rename URLDissector to FractionReader (class name and file name)
   * Rename url and urlScan to be appropriately named for fractions.
   * Change ```urls.inp``` to ```fractions.txt```.
2. Add an ArrayList of Fractions.
3. Remove the nested while loop and instead read 2 strings and convert them to integers, using ```Integer.parseInt(*the string value*);```
4. Create a Fraction object with the 2 integers and add it to the ArrayList.
5. Add a loop to the end to print the Fractions from the list in reverse order (elements size-1 to 0).
6. Remove unnecesary prints.

## Submission
Submit your source code to CodePost.

