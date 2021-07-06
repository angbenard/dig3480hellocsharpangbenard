# Tutorial 1: Getting Started

This repository is used for the first coding assignment in DIG3480.

The steps are outlined both here as well as in the README.md file in the repository.

For this simple introduction to C#, we are going to be working in a pre-created scene provided in this project.

Follow the video walkthrough in order to modify two files in the Unity Project, "Assets/Scripts/Names.cs" and "Assets/Scripts/Numbers.cs" you cloned in the previous assignment.

These two files represent "classes", or collections of methods and variables that perform operations. Your code will be called by other classes, including the "OutputScript" which renders the variables and allows you to call them with buttons, and the Tutorial1Tests which will evaluate your methods and compare the return values to the expected values.

Each of the criteria is evaluated using an automated test, explained below.

You can verify your work using the Test Runner built into Unity. If you run into any errors, please reach out to me on WebCourses.

The unit tests are described here and will be elaborated on in future tutorials and quizzes.

Files to Edit. You must edit each method to pass the tests described below.

Assets/Scripts/Names.cs
Assets/Scripts/Numbers.cs

Tests to Pass: (Test Precedes the Method Name)

- **TestHelloWorld**: [names.cs] Modify the "SayHello()" method in names.cs to return the string "Hello World" |
- **TestGreaterThan**: [numbers.cs] Modify the "GreaterThan" method to returns true (the boolean value) if the first argument is greater than the second argument passed into the method. If "memberA" is 10 and "memberB" is 20, then GreaterThan() should return false.
- **TestSumTwoArguments**: [numbers.cs] Modify SumTwoArguments to return the sum of the two integer arguments, using the parameters. For instance, SumTwoArguments(1,3) should return the integer 4, while SumTwoArguments(3,8) should return 11.
- **TestSumTwoMembers**: [numbers.cs] Modify SumTwoMembers() to returns the sum of the two member variables "memberA" and "memberB" in the class, which will be set by a function outside of the class. For instance, numbers.SumTwoMembers() with memberA = 10 and memberB= 20 would return 30.
- **TestUseGreeting**: [names.cs] Returns the "name" member variable appended to the end of the argument passed into the method. E.g. "Hi there " with the name variable set to "John" would produce "Hi there John".

Note it should not add any spaces to the greeting passed in.
