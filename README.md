# SuperDuperTeam2

## Super Duper Best Practices

### All naming should represent the intention of the subjects purpose

## Linting//TODO:
-https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp


## files
-Both File and Folder names must be done with Pascal Casing

## Class Names
-Each class should not violate the Single Responsibility principle ...or else
-Pascal case naming

## Interfaces
-interfaces should start with I
-should never have variables declared in 
-no definitions allowed in interfaces

## Variables
-It is not permitted to declare several variables in a single line.
-when declaring a variable of type Boolean the variable should start with 'Is'

## functions
-If a function is used in mutliple packages, it should be extracted into the utils directory and imported.
- Avoid long functions, function should be small
- Functions should be encapasulates if not used outside the class (Implementation should be private) 

## Unit Tests
-Test what you make 

Commentted code should be removed before PR
Study the documentation and test the third API before you start using it.

## Heavy Considerations  
- in the event that a function has more than 3 parameters consider wheteher or not that function is following the Single Responsibility principle.
- Duplicate Code should be abstracted into method

<Add some text around the application of documentation>
C# Standard Practice
https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions
