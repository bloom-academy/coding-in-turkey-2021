# Problem 1: Validate Recipe

We are building an application that helps chefs determine if they're able to cook a certain recipe. For a recipe to be possible, the chef must have all its ingredients available in the fridge.

## What to submit

1. A function with the name `validateRecipe`.
    - Your function must:
      - Receive two variables:
        - `fridge`: is a string array containing all items currently available in your fridge.
        - `ingredients` is a string array of items you need to be able to cook a certain meal.
      - Example 1 (should return `false`):
        ```js
        ingredients = ['tomato', 'onion', 'lettuce']
        fridge = ['tomato', banana', 'apple', 'onion', 'cucumber']
        ```
      - Example 2 (should return `true`):
        ```js
        ingredients = ['olives', 'onion', 'lettuce']
        fridge = ['onion', banana', 'lettuce', 'olives']
        ```
      - Return `true` if the chef is able to cook the given meal.
    - For example, if you write your function in JavaScript, it would look something like this:
      ```js
      function validateRecipe(fridge, ingredients) {
        // complete this function
      }
      ```

1. Write your code, in the language of your choice, inside a file with the name `problem1-solution-[firstname]-[lastname].[ext]` where:
    - `[firstname]` is your first name spelled the same as you wrote it in the application form.
    - `[lastname]` is your last name spelled the same as you wrote it in the application form.
    - `[ext]` is the extension of the programming language you're using, such as `js`,`ts`,`go`,`c`,`cpp`, `py`, `rb`, etc.
    
    For example, if you wrote your solution in JavaScript and your name is "Sara Al-Tamawi", you should write your code in a file with the name `problem1-solution-sara-al-tamawi.js`.

1. Store the value returned by `validateRecipe` function, and print it out to the screen (i.e. `console.log()` in JS).

### Optional Extra Credit

If you found it easy to solve the problem above, you can claim some extra credit by doing the following. Note that these are all **optional**. You should still submit your solution if you can't do any of these extra requirements.

1. Make your program read the input from command line arguments, STDIN, and/or a JSON file with the name `inputs.json`.
1. Submit a second file with the name `run.sh` which uses `bash` scripting to run your solution file. For example, if your solution is written in javascript, the bash script content might look like this:

    ```bash
    node problem1-solution-sara-al-tamawi.js
    ```
1. Write automated unit tests for your function.
