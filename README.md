> **Pair programming exercise**
>
> * Fork and clone repo
> * Write a solution to each exercise and a corresponding test which ensures correctness of solution
> * Try to write the test before writing the solution. This will force you to think closely about the task
> * One person should be writing the test and another the solution. Alternate roles after each exercise
> * For some tests you may have to write several test cases to make sure all edge cases are covered
> * Run `npm test` regularly to ensure your tests pass
> * Commit and push after each solution created
> * Create a pull request after first push
>
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
> * `developer` - Write a function a constructor called `Developer` which receives 2 parameters an input string containing name and an array of programming languages the developer knows
> * `inherit` - using prototypal inheritance add a function called learn language, which accepts a new language in string format and adds it to array of programming languages the developer knows. The values in array should be unique
> * `garden` - create a constructor called Garden. It should receive an object as input which contains names of plants as keys and numbers as corresponding quantities as values
> * `extend` - using prototypal inheritance add a method called `plant` which receives an object of plants and corresponding quantities as keys and adds them to current stock
> * `harvest` - using prototypal inheritance add a method called harvest to garden. It should receive and object which contains plant names as keys and quantities to harvest as values. Reduce the quantity of existing plants in garden by the number of plants to be harvested. If number of certain plant falls to 0 or below. Remove key from corresponding object
> * `stringsConcat` - Write a function which receives an array of strings and numbers. The function should concatenate all strings and return the resulting string.
> * `negativeOnly` - Write a function which receives one array of positive and negative numbers. It should return an array containing only the negative numbers
> * `camelise` - Write a function which receive a string of lower case, space separated words. It should convert the string to camel case. That is capitalise the first letter of every word except the first and remove all spaces
> * `merging` - Write a function which receives an array of objects. It should merge them into a single object. The objects with fewest values should take precedence over objects with fewer values. The input objects should remain unaffected, by the merge. For example input `[{a: 5}, {a: 3, b: 21, c:32}]` to `{a:5, b:21, c:32}`
> * `possibleValues` - Write a function which receives an array of objects. Your function should output an object which contains all the keys from input objects. The corresponding value of each key should be an array which contains a list of all values the corresponding key had in all input objects. Values should be unique. For example `[{a: 5}, {a: 3, b: 21, c:32}, {a: 3, c:32}]` to `{a:[5,3], b:[21], c:[32]}`
> * `isPrime` - Write a function which receives an integer an returns `true` if the input is a prime number, `false` otherwise
> * `walkabout` - write a constructor called Walker. It should receive one parameter, a string which is either 'N', 'S', 'E' or 'W' which indicates the direction the walker is facing. Walker's initial coordinates should be (0,0), where the first coordinate represents the x coordinate (horizontal) and the second coordinate represents y coordinate (vertical).
> * Add a `walk` method to `Walker` using its prototype which accepts a direction as a string and a number representing the number of steps to be taken. When called the walker should update its coordinates and add the move made to its journey history. The journey history should be stored using coordinates representing the location at the end of each move.
> * Add a `pathTaken` method to `Walker` using its prototype. It should output the journey taken taken as a list of coordinates
