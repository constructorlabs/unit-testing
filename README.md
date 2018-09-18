> **Pair programming**
>
> * Fork and clone repo this repo
> * run `npm install` after cloning to download external dependencies
> * Write a solution to each exercise and a corresponding test which ensures correctness of solution
> * Try to write the test before writing the solution. This will force you to think closely about the task
> * One person should be writing the test and another the solution. Alternate roles after each exercise
> * Create at least two test for each question to cover different inputs and outputs
> * Run `npm test` regularly to ensure your tests pass
> * To run all tests in the background continuously you can do so using `npm test -- --watchAll`


> **Exercises**
>
> * `longestString` - Write a function which receives an array of strings. It should return the longest string from the array
>
> * `l337` Write a function which receives a string. It should replace all instances of letters below with corresponding number and return the resulting string
>   1. `i` or `l` with number 1
>   2. `z` with the number 2
>   3. `e` with number 3
>   4. `a` with number 4
>   5. `s` with number 5
>   6. `g` with number 6
>   7. `t` or `y` with number 7
>   8. `b` with number 8
>   9. `q` with number 9
>   10. `o` with number 0
> * `uniqueStrings` - Write a function which receives an array of strings. It should return an array of unique strings from the input array
> * `developer` - Create a constructor called `Developer` which receives 2 parameters an input string containing name and an array of programming languages the developer knows
> * `learn` - using prototypal inheritance add a method to `Developer` called `learnLanguage`, which accepts a new language in string format and adds it to array of programming languages the developer knows. The values in array should be unique.
> * `stringsConcat` - Write a function which receives an array of strings and numbers. The function should concatenate all strings and return the resulting string.
> * `negativeOnly` - Write a function which receives one array of positive and negative numbers. It should return an array containing only the negative numbers
> * `camelise` - Write a function which receive a string of lower case, space separated words. It should convert the string to camel case. That is capitalise the first letter of every word except the first and remove all spaces

> **Stretch goals**
>
> * `isPrime` - Write a function which receives an integer an returns `true` if the input is a prime number, `false` otherwise
> * `walkabout` - create a constructor called `Walker`. Walker's initial coordinates should be (0,0), where the first coordinate represents the x coordinate (horizontal) and the second coordinate represents y coordinate (vertical).
> * Add a `walk` method to `Walker` using its prototype which accepts a direction as a string and a number representing the number of steps to be taken. When called the walker should update its coordinates and add the move made to its journey history. The journey history should be stored using coordinates representing the location at the end of each move.
> * Add a `pathTaken` method to `Walker` using its prototype. It should output the journey taken taken as a list of coordinates
