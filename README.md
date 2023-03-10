# Super Duper Team 2 Best Practices

Ensure you read through and understand the documentation before starting any development work. The intent of this document is to cover the standard practices the group follows for the C# programming language and also a guide to setting up and installing all the tools needed to run the project. An effort should be made at all times to adhere to these practices.
 
## IDE
### Installation
   The editor chosen by this team is Microsoft's Visual Studio. Below is a link to a guide to download, install and configure Visual Studio on your machine.
 - [IDE setup](https://learn.microsoft.com/en-us/visualstudio/install/install-visual-studio?view=vs-2022)
  
### Getting Started
   Please follow this guide to understand how to use the IDE as it covers a range of important and effective functionality.
 - [Getting Started](https://learn.microsoft.com/en-us/visualstudio/get-started/csharp/visual-studio-ide?view=vs-2022)
 
## Linting
   We make use of a C# linting extention called Cshapier with its deafult configurations to automatically format our code before commit or pushing code.
   Install the linter on your Visual Studio using the link above and follow the installation instructions.
 - [csharpier](https://github.com/belav/csharpier)
   
 ## C# Conventions
   We follow most of the conventions defined in the C# documentation but we have listed preferences and some important aspects we wish to be applied
   throughout the developemt of this project as well as some things to keep in mind. Please make sure you are familar with the coding 
   conventions in the official C# documentation a well as the teams documentation.
 - [C# Coding Conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)

## General
 - All naming should represent the intention of the subjects (files, folders, functions, variables, etc...) purpose.
 - Commented code should be removed before PR (Pull Requested).
 
## Files
 - The names of files and folders must be written using Pascal Casing.
 
## Formatting rules
 - Must indent the logic inside the methods.
 - Must have spaces after the if,else statements and loops.
 - Must have a new line before the catch and finally blocks.
 - Must have a new line before and after the curly-braces.
 - Must indent switch labels and case statements in switch statements.
 - Add space before and after the assignment operator.
 
## Class Names
 - Each class should not violate the Single Responsibility Principle (SRP).
 - Pascal case naming.
 - Class name should be a noun, not a verb.

## Interfaces
 - Interfaces should start with I (e.g. "IGetUserData" as opposed to "GetUserData").
 - Should never have variables declared in an interface.
 - No function definitions/implementation are allowed in an interface.

## Variables
 - It is not permitted to declare several variables in a single line.
 - When declaring a variable of type Boolean the variable should start with 'Is'.
 - Avoid abbreviation when declaring variables.
 - Constant variables should follow Snake case naming with upper case letters  (e.g MINIMUM_VALUE).
 - Standard variables should follow Camel case naming.

## Functions
 - If a function is used in mutliple packages, it should be extracted into the common directory such as the Utils directory and imported.
 - Avoid long functions, function should be small.
 - Functions should not violate the SRP.
 - Functions that are used only within that class should be encapasulated.
 - Don't return null or pass in null in any code pushed to the repo.
 - Functions should follow Pascal case naming.
 - Avoid static methods as they violate SRP.
## Unit Tests
 - Test each function that you create. 
 - Test code must be designed to be read.
 - Tests should not violate SRP.

## Heavy Considerations  
- In the event that a function has more than 3 parameters consider whether or not that function is following the SRP.
- Avoid Duplicate Code
- Regions are considered anti-patterns, as they require more work which does not increase the quality/readability of the code. Do not use them.
