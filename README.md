This assessment will test your knowledge of variables, conditionals, functions, arrays, and loops. Fork and clone the following starter repo and get started solving some problems with JavaScript!

*Starter Repo*: [https://gitlab.com/kenzie-academy/se/fe/js-basics](https://gitlab.com/kenzie-academy/se/fe/js-basics)


# Fizz Buzz

FizzBuzz is a common programming puzzle. It requires that you use both loops and conditionals. Variations of this puzzle are widely used as an initial screening question during job interviews. Because this is a classic puzzle, it's easy to look up solutions online. It will be good practice for you to first try to solve the puzzle yourself before searching online.

- Write a function named `fizzBuzz` that takes one parameter: `maxValue`.
- This function should loop through 1—`maxValue` (inclusive) and build a string with the following conditions:
  1. If a number is even, concatenate `"Fizz, "` to the end of the string.
  2. If a number is a multiple of 3, concatenate `"Buzz, "` to the end of the string.
  3. If a number is both even and a multiple of 3, concatenate `"FizzBuzz, "` to the end of the string.
  4. If a number is neither even or a multiple of 3, concatenate the number and `", "` to the end of the string.
  5. This function should `console.log()` the final string after `maxValue` iterations of the loop.

## Example Output

`fizzBuzz(12)` should output the string `1, Fizz, Buzz, Fizz, 5, FizzBuzz, 7, Fizz, Buzz, Fizz, 11, FizzBuzz, ` to the console.

# Gettysburg

You are provided a string representation of the Gettysburg Address. Write a function that prints one word of the Gettysburg Address at a time in the console.

## Example Output
`gettysburging()` should output to the console `'Four'`, then `'score'`, then `'and'`, then `'seven'`, and so on until the end of the address.

# Virginia

Count the number of times you find "Virginia" in a string that is unreasonably long and full of strange characters.


## Example Output
`countVirginia()` should output to the console the number of times the word "Virginia" is found in the string.

# Ascii art lol

We are using JavaScript to display some cool art in our HTML page but something isn't right. See if you can review scramble.js to help you understand what you have to do to the artArray in `exercise02.js` before `writeAscii()` uses it to display the messed-up image on the page.

## Example Output
`writeAscii()` should update the attached index.html page so that the ascii art of the dollar bill is no longer scrambled. It should look like this:

![example](./04-ascii-art-lol/example.png)

# setTimeout

For this exercise you will be working with the `setTimeout()` function in JavaScript. Your task is to update some text in the HTML file 3 seconds after the page has loaded. See `exercise06.js` for all the details.

## Example Output
![example](./05-set-timeout/example.gif)

# Images In Time

For this exercise you will add a random image to the page every 2.5 seconds using the `setTimeout()` function in JavaScript. This would be easier with `setInterval()` but what fun would that be? Don't worry, we have included some hints in `exercise07.js`

## Example Output
![example](./06-images-in-time/example2.gif)