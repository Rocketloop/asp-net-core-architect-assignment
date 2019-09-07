# Backend Assignment: Simple Middleware

The assignment involves the creation of a simple Middleware for ASP.NET Core. Please use the following libraries and versions:

* ASP.NET Core 2.2+

**Updated @ Apr'19**

## Simple ASP.NET Core Middleware (1-2h)

Create a middleware in a ASP.NET Core that implements the following functionality:

* Replace `rl` with `rocketloop` in all values of JSON requests
* The middleware should only trigger for a configurable list (regular expressions) of endpoints
* Write tests using XUnit for requirements mentioned above 

## Architecture and Design (30m - 1h)

There are numerous project design patterns that can be used in ASP.NET Core applications. Two very common patterns are either organizing files with similar functions in common folders and namespaces (e.g. Data, Services, Filters, etc.) and organizing files with a similar scope in one folder and namesspace per feature (e.g. Register/Models, Register/Filter, Register/Controllers, etc.) (feature folders). 

Please discuss the arguments for and against both patterns in a few bullet points and explain which pattern you'd prefer for a simple CRUD web API and why.

## API Design (1h)

Describe (in text or as swagger) the REST API design for the following application: 

A customer wants to implement a simple TODO List application: Todos are organized as lists of simple todos (text + status). Multiple lists are organized as one board (both only having a title). A user is able to create, update and delete boards, lists and todos they have access to. By default a user has access to the boards they have created. A user is able to invite other users to a board he created. For this assignment you can ignore other user related logic (registration, password reset, etc). 

## How to work on the assessment

*   Fork this repository
*   Start working on the assignment
*   Please do periodic commits with meaningful commit messages
*   Once you are done push your final results
*   If you don't want to create a public repository please invite (@phelmig, @erzaehlsalex, @flore2003) to your working repository
*   Please include a brief description how to run your solution
*   If you have any questions contact us (jobs@rocketloop.de)

Please note that we don't accept solutions without periodic commits or if we are unable to execute the solution.

