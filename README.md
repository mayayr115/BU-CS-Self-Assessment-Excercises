# BU-CS-Self-Assessment-Excercises
## Straightforward Coding Problems

The coding problems below apply to high level programming languages such as C, C++, Java, Pascal, Fortran, Python, Matlab, and Visual Basic.Experience with markup languages such as HTML does not constitute adequate programming experience to bypass CS 110; the skills needed to construct a Web page, or a Flash-based application, are not enough.

**1.** [This is not a programming problem, it is a few questions about programming.] Programmers use an editor to create the source code, a compiler to build an executable, and some kind of execution environment within which to run the program. When programming, what is your preferred editor, what is your preferred compiler, and how do you run programs that you created on your preferred system? [Once you have programmed “enough”, these answers will leap to mind immediately. If you’re inexperienced, you may not even fully understand the concepts of editors, compilers, and execution environments.]

For the rest of the exercises, you may use a programming language of your choice. If that language requires variables to be "declared," then provide the declaration for any variables used, and write programs that (would) run properly. Don’t be satisfied thinking “I could figure this out if I had to”; that should be true of all of them. We’re hoping to determine whether you’ve reached a point where all of these exercises are very simple and straightforward for you already. Be honest with yourself so that you’re placed in the proper course for you.

**2.** Write a complete “Hello World” program (not pseudocode) that is syntactically correct and runs properly the first time you try it.

**3.** Write a sequence of statements that assigns the value 3.14159 to a real-number variable named pi and assigns the character 'Z' to the variable z. [This exercise should take not much longer than the time it takes to type the code, and should compile and run on the first or second attempt.]

**4.** Write a statement that assigns to the integer variable named day_of_year the day of the year that is July 6. (Jan 1 is day 1, Jan 2 is day 2, etc.), and then prints that number. The program should “hard code” variables or constants as necessary (for the number of days in each month, for example), and should work correctly during a leap year. It should also be structured such that July 6 could be changed to any other date and the program would still run properly.

**5.** Write a loop that calculates and prints out the sum of the squares of all the integers from 1 to 100. [Ideally, you could write this easily using multiple different kinds of loops… for, while, repeat-until, etc., depending on the language].

**6.** Write a function (or method) dayOfYear(month, dayOfMonth, year) that returns the day of the year, given the three integer arguments. For example, dayOfYear(2, 12, 2023) should return 43.  [If your instinct was to write a function for #4 above, that’s a good sign!]

**7.** A fraction such as 2/3, 19/7, etc., can be represented as a pair of numbers in a struct, record, class object, or tuple, depending on the language. Make an appropriate choice for your preferred language and write a function that takes two fractions as parameters and returns their sum (which is itself a fraction).

**8.** Write a function that has integer parameters m and n and, if 0 < m < n, the function computes the sum of the
numbers 1/m, 1/(m+1), 1/(m+2), ..., 1/n, and otherwise returns 0.

**9.** Given three integer variables a, b and c as the coefficients of a quadratic equation ax2 + bx + c = 0, write an expression that is true if the equation has two equal roots. (Note that quadratic equations are taught in the first algebra course.)

**10.** Assume that abs() is a function that has one integer parameter and returns the absolute value of that integer. Write an expression that computes and returns the sum of the absolute values of two integer parameters a and b.

**11.** Write the code for the function abs(). Call your function myabs() to avoid possible conflict with a built-in function (depends on the language).

**12.** Write a function hypotenuse() that has two real numbers as input parameters, representing the two shorter sides of a right-angled triangle, and returns the length of the hypotenuse of that right-angled triangle. You should find and use your language’s square-root function.

**13.** Write a program that will input a name (reading from the keyboard in some manner), and print out the number of letters (a-z, A-Z) in the name. The program should ignore spaces and punctuation.

**14.** Read the following explanation of Newton's method below and write a function squareRoot(x) that
computes the square root of x using Newton's method. The function should use a loop that should end when the approximation is within .00001 of the true square root.

"A common way to compute the square root is to use Newton's method of successive approximations. Newton's method says that whenever we have a guess y for the value of the square root of a number x, we can perform a simple manipulation to get a better guess (one closer to the actual square root) by averaging y with x/y. For example, we can compute the square root of 2 as follows. Suppose our initial guess is 1:

<img width="443" alt="Screenshot 2025-06-05 at 5 41 37 PM" src="https://github.com/user-attachments/assets/c637ed5a-17d3-4664-81d2-aa97faf62440" />

Continuing this process, we obtain better and better approximations to the square root."
(From Structure and Interpretation of Computer Programs by Abelson and Sussman).
