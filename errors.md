1. Missing Semicolon

   PS E:\Halel\Downloads\cit4040-Khalel> javac src/Main.java
   src\Main.java:3: error: ';' expected
   String name = "Khalel"
   ^
   1 error

Semicolon after Khalel is missing 

2. Misspelled println

PS E:\Halel\Downloads\cit4040-Khalel> javac src/Main.java
src\Main.java:7: error: cannot find symbol
System.out.printline("Hi, " + name);
^
symbol:   method printline(String)
location: variable out of type PrintStream
1 error

Java cant find missppelled method 

3. Wrong data type

PS E:\Halel\Downloads\cit4040-Khalel> javac src/Main.java
src\Main.java:4: error: incompatible types: String cannot be converted to int
int a = "twelve";
^
1 error

text stores in int variable

