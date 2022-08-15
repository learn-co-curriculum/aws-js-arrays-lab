# Arrays Lab

## Learning Goals

- Practice writing arrays
- Practice using _destructive_ methods to manipulate arrays
- Practice using _nondestructive_ methods to manipulate arrays

## Introduction

We've learned about how arrays work and about the array methods built in to
JavaScript that we can use to manipulate them. Now it's time to practice what
we've learned.

If you haven't already, fork and clone this lab into your local environment.
Navigate into its directory in the terminal, then run `code .` to open the files
in Visual Studio Code.

Install all the dependencies with `npm install` to ensure you can test your work as 
you go with `npm test`.

## Instructions

Run `npm test` and read through all the tests you need to pass. These tell you the 
names of the functions you need to define and what each one should do. Note that some of
the names of the functions you will be writing begin with `destructively` and
some don't. This is a clue as to which `Array` method you will need to use for
each function.

Do your work in the given `index.js` file. In that file, you're provided with an array 
called `cats`, set to an initial value of `["Milo", "Otis", "Garfield"]`. In your functions, 
you will be accessing and manipulating this array.

Remember the workflow:

1. Run the tests using `npm test`.
2. Read the errors; vocalize what they're asking you to do.
3. Write code; repeat steps 1 and 2 often until a test passes.
4. Repeat as needed for the remaining tests.

> **NOTE**: Although we're practicing both destructive and nondestructive methods in this 
> lab, keep in mind that in production it's generally good practice to avoid mutating a program's 
> state whenever possible. When using nondestructive methods, we have complete control over
> what's going into and coming out of the function. This makes our programs more robust, easier 
> to maintain, and less prone to bugs.

