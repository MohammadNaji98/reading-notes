# **Reading Notes**

## Description:

This site where i can keep track of my observations and questions from the reading assignments throughout my course.
<br><br><br><br>

* ## ***Code 102 - Intro to Software Development.***

<br><br>

* ## ***Code 201 - Foundations of Software Development.***

<br><br>

* ## ***Code 301 - Intermediate Software Development.***

<br><br>

* ## ***Code 401 - Advanced Software Development.***


### Exception Handling:

When the programmer writes the code, he tries as much as possible to find solutions to the problems that the user may encounter at the time of execution.
For example, when the user of the program divide by number 0, and as it is known, this is mathematically wrong and can cause many problems, for example, what if the program is designed for the sensitive medical sector such as radiation therapy!! as [Therac-25](https://en.wikipedia.org/wiki/Therac-25) for example.

Therefore, the programmer anticipates the errors that the programmer may fall into when using, and then puts the code that depends on the user’s input in a place to experiment and anticipate the error
Like Try and Catch
In this way, the programmer will protect his program from errors, from suspension, and from errors that result from misuse of the program.
[How to debug for absolute beginners](https://docs.microsoft.com/en-us/visualstudio/debugger/debugging-absolute-beginners?view=vs-2019&tabs=csharp)



* for example in C# :

```C#
var value=int.Pars(Console.ReadLine());
var resule;
try{
    resule/=value;
}
catch(DivideByZeroException)
{
Console.WriteLine("Divide by zero is Arithmetic error :)");
}

```
<br><br><br><br>
> This site was built using ***[GitHub Pages](https://github.com/MohammadNaji98/reading-notes)*** by ***[Mohammad Naji Alkhresheh](https://twitter.com/Mohammad_Naji10).***
