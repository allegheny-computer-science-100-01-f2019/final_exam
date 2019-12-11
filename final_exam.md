## CMPSC 100 Final Exam
### Name:


### Question 1
Explain (in a few sentences) how object-oriented nature of Java can be used in the computational thinking process.


### Question 2
Which of the following classes is a part of the java.lang package? Put x inside brackets to indicate the chosen answer.
- [ ] Scanner
- [ ] Random
- [ ] Math
- [ ] Date


### Question 3
What is printed to the terminal by the following Java statements?

```
int num1 = 2;
int num2 = 5;
System.out.println("num1 * num2 = " + (num1 * num2));
System.out.println("\\\\//");
System.out.println("num1 + num2 = " + num1 + num2);
```


### Question 4
Assume that you are in the directory named `midterm` in the terminal that contains a file  `midterm_exam.md`. What command do you need to type in the terminal to commit a file called `midterm_exam.md` to your GitHub repository on the Web? Put x inside brackets to indicate the chosen answer.

- [ ] git commit midterm_exam.md -m "Adding midterm"
- [ ] git add midterm_exam.md -m "Adding midterm"
- [ ] git commit "Adding midterm"
- [ ] git commit midterm/midterm_exam.md -m "Adding midterm"


### Question 5
What are the final values of variables `num1`, `num2`, `num3`, and `num4` in the following code?
```
int num1 = 10;
int num2 = 20;
double num3 = num1 / num 2;
double num4 = num1 / (double) num2;
num1 = num1 * num4;
num2 = (int) (num2 * num4);
```


### Question 6
Define and give an example for each of the following terms: (a) reference data type; (b) primitive data type; (c) casting; (d) promotion


### Question 7
Write Java statements to set variable `num` to a random integer between 1 and 6 (including but not exceeding 6), i.e., a number that is either 1, 2, 3, 4, 5, or 6. You may assume that an instance of the Random class has been created (as: `Random rand = new Random();`;) and that variable `num` has been initialized to a value of an `int` data type.


### Question 8
Each of the following sequences of Java statements contains a compiler error. State what the error is.

* a)

```
public static void main (String [ ] args) {
   System.out.println("Hello World")
}
```   

* b)   

```
Scanner input = new Scanner (System.in);
String line = input.nextLine();
String characters = line.length();
```

* c)

```
int num = 5 / (double) 2;
```

* d)

```
Random random = new Random;
```

### Question 9
Something is wrong with each of the if and if/else statements below. All the errors are the errors that prevent you from executing the program. Find the errors and correct them. (NOTE: assume that all variables are properly declared and initialized; the errors lie in the formation of the if statements themselves, not elsewhere in the program.)

* a)

```
if (num1 = 10) {
   num2 = num1;
}
```

* b)

```
if (num1 =< 10) {
   num1 = num1;
}
```

* c)

```
if (num1 != 10) {
   num2 = num1;
}; else {
   num2 = 10;
}
```

* d)

```
if (num1 && num2 >= 10) {
   num2 = num1;
}
```   


### Question 10
Suppose `line` is a String variable containing a line of text. You may assume that the line of text may contain any mixture of letters, spaces, numbers, punctuation marks, etc. You may also assume that the string has at least two characters in it. Complete the Java statements needed to print each of the following values.
* a) The length of the string `line`.

* b)  The string `line` with all letters changed to upper case.

* c) The middle character of `line`. You can assume that the middle position is the length of `line` divided by 2, no matter whether the length is even or odd.

* d) The last three characters of `line.`


### Question 11
Which of the following is NOT a computational thinking technique? Put x inside brackets to indicate the chosen answer.
- [ ] Decomposition
- [ ] Pattern recognition
- [ ] Programming


### Question 12
Something is wrong with each of the while statements below. In some cases the errors will cause the compiler to emit error messages and prevent you from executing the program. In others, the program will compile without error, but will issue a run-time error during the execution of the program. Find the errors and correct them. (NOTE: assume that all variables are properly declared and initialized - the errors lie in the formation of the `if` and `while` statements themselves, not elsewhere in the program.)

* a)

```
int num = 0;
while (num = 0) {
    num++;
}
```

* b)

```
int num = 0;
while (num != 10) {
    System.out.println("Number is " + num);
}
```

* c)

```
int num = 10;  
while (num1 || num2 >= 2) {
    num--;
}
```

### Question 13
Which of the following is NOT a valid identifier? Put x inside brackets to indicate the chosen answer.
- [ ] num1
- [ ] Num
- [ ] num_1
- [ ] 1num


### Question 14
What is meant by "healthy internet"? From the assigned readings, what can computer scientists do to build healthier internet for all?


### Question 15
Assume there is a text file titled `input.txt` that contains the following:

```
Night, street, lamp, drugstore,
A dull and meaningless light.
```

What will be printed by the following Java statements?

```
File inputFile = null;
Scanner scanner = null;
try {
   inputFile = new File("input/Ulysses.txt");
   scanner = new Scanner(inputFile);
} catch (FileNotFoundException noFile) {
   System.out.println("Unable to locate file");
}
int count = 0;
while (scanner.hasNext()) {
   String text = scanner.next();
   count++;
   System.out.println(count + ": " + text);
}
```
