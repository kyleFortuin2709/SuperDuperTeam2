# Group 2 Best Practices

## Linting//TODO:
 - [C# Lint](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
 
 ## C# Conventions
 - [C# Coding Conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)

## General
 - All naming should represent the intention of the subjects purpose
 - Commented code should be removed before PR (Pull Requested)
 - Study the documentation and test the third API before you start using it.
 
## Files
 - The names of files and folders must be written using Pascal Casing.

## Class Names
 - Each class should not violate the Single Responsibility Principle(SRP)
 - Pascal case naming
 - Class name should be a noun, not a verb.

## Interfaces
 - Interfaces should start with I
 - Should never have variables declared in 
 - Avoid definitions/implementation in interfaces

## Variables
 - It is not permitted to declare several variables in a single line.
 - When declaring a variable of type Boolean the variable should start with 'Is'
 - avoid abbreviation when declaring variables

## Functions
 - If a function is used in mutliple packages, it should be extracted into the common directory such as the Utils directory and imported. { A function should be extracted into a shared location, like the Utils directory, and imported if it is used in more than one package. }
 - Avoid long functions, function should be small.
 - Functions should not violate the SRP.
 - Functions that are used only within that class should be encapasulated.
 - Don't return null or pass in null

## Unit Tests
 - Test what you make 
 - Test code must be designed to be read

## Heavy Considerations  
- In the event that a function has more than 3 parameters consider whether or not that function is following the SRP.
- Avoid Duplicate Code
