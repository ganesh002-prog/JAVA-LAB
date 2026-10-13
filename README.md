# JAVA-LAB

Java lab programs, organised by experiment. Each file has the Aim and Algorithm in a comment at the top, the program, and the Result in a comment at the end.

## Programs

| Experiment | Program | What it does |
|---|---|---|
| EXP1 – Arrays | [AscendingOrder.java](EXP1/AscendingOrder.java) | Sorts array elements in ascending order |
| | [BinarySearch.java](EXP1/BinarySearch.java) | Searches an array using binary search |
| | [LargestSmallest.java](EXP1/LargestSmallest.java) | Finds the sum, largest and smallest number in an array |
| | [printmarksabove.java](EXP1/printmarksabove.java) | Lists students who scored 60 or above |
| EXP2 – Conditionals | [ArithmeticOperators.java](EXP2/ArithmeticOperators.java) | Menu-driven calculator using `switch` |
| | [EvenOdd.java](EXP2/EvenOdd.java) | Checks whether a number is even or odd |
| | [Largestofthree.java](EXP2/Largestofthree.java) | Finds the largest of three integers |
| | [LeapYear.java](EXP2/LeapYear.java) | Checks whether a year is a leap year |
| EXP3 – Loops | [Armstrong.java](EXP3/Armstrong.java) | Checks whether a number is an Armstrong number |
| | [FibonacciSeries.java](EXP3/FibonacciSeries.java) | Prints the Fibonacci series up to n terms |
| | [MulTable.java](EXP3/MulTable.java) | Prints the multiplication table of a number |
| | [Perfectnumber.java](EXP3/Perfectnumber.java) | Checks whether a number is a perfect number |
| | [Reversenumber.java](EXP3/Reversenumber.java) | Reverses an integer |
| EXP4 – Strings | [Replace.java](EXP4/Replace.java) | Replaces a substring using `replace()` |
| | [SubstringsOfAString.java](EXP4/SubstringsOfAString.java) | Prints and counts all substrings of a string |
| EXP5 – Classes | [ArithmeticOperators.java](EXP5/ArithmeticOperators.java) | Arithmetic operations using separate classes |
| | [perimeterandarea.java](EXP5/perimeterandarea.java) | Area and perimeter of a square, circle and triangle |
| EXP6 – Interfaces | [StuDetail.java](EXP6/StuDetail.java) | Student details and percentage using inheritance and an interface |
| | [Volumeinterface.java](EXP6/Volumeinterface.java) | Volume of a cylinder and a sphere using an interface |
| EXP7 – Inheritance | [AccountDemo.java](EXP7/AccountDemo.java) | Bank account and savings account |
| | [College.java](EXP7/College.java) | College and Department classes |
| EXP8 – Threads | [CreatingsimpleThread.java](EXP8/CreatingsimpleThread.java) | Threads with `yield()`, `sleep()` and `break` |
| | [ThreadPriority.java](EXP8/ThreadPriority.java) | Thread priorities |
| EXP9 – Files | [Filewriter.java](EXP9/Filewriter.java) | Writes A–Z to `sample2.txt` |
| | [Filereader.java](EXP9/Filereader.java) | Reads and prints `sample2.txt` |
| EXP10 – Applets (AWT layouts) | [insertdemo.java](EXP10/insertdemo.java) | BorderLayout |
| | [gld.java](EXP10/gld.java) | GridLayout (5 rows × 2 columns) |
| | [carddemo.java](EXP10/carddemo.java) | CardLayout |

## Running a program

```
cd EXP2
javac EvenOdd.java
java EvenOdd
```

Run `Filewriter` before `Filereader`, since it creates `sample2.txt`.

The EXP10 programs are applets. They compile on current Java versions, but running them needs `appletviewer`, which was removed after Java 8.
