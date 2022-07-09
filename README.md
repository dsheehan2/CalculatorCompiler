*Program written in Java*

--What this Program Does--
- This program follows a DFA (Deterministic Finite Automaton) in which a scanner will read user input and determine tokens to be parsed and categorize them for the compiler to use and understand each input.
- After typing any type of syntax a calulator will use such as "5 * 5 + (7 / 2) + 4" (remove qoutes), the decent parser will print each category what the tokens represent.
- This program reads single line comments "//" or block comments "*/" in Java style for the user input into a file.
- ":=" means assign and the scanner and parser will recognize variables such as "x" or "y" if needed.
- Please check "test1.txt" to see how this program runs. This text file provides an example (Beta is assigned to a decimal number and Alpha is assigned to an integer in parentheses). 
- After running, you will see the recursive descent parser based on the example given.
- You may input any syntax a calculator would use into "test1.txt" or any other text file you add to the program. 
- No need to add braces or terminators (semicolons) for input into console.

--How to Use--
1. From command prompt, navigate to folder containing java files
2. Type javac parser.java
3. Press Enter
4. Type javac scan.java
5. Press Enter
6. Type javac main.java
7. Press Enter
8. Type java main fileNameOfTestCase.txt
9. Press Enter
10. File should print to console
