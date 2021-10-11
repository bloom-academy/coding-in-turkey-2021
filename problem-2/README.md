# Problem 2: Validate Recipe with Quantity

Our recipes are now more complicated and we have to know the quantity of each item to know if we can cook it.

## What to submit

1. A function with the name `validateRecipeWithQuantity`.
    - Your function must:
      - Receive two variables:
        - `fridge`: contains an association between each item and how many of it we have (you may know this as map, dictionary, object or table) available in the fridge.
        - `ingredients` contains an association of each item and how many of it are required to make the meal.
      - Example 1 (should return `false`):
        ```js
        ingredients = {'tomato': 1, 'onion': 2};
        fridge = {'tomato': 1, 'onion': 1};
        ```
      - Example 2 (should return `true`):
        ```js
        ingredients = {'tomato': 2, 'onion': 3};
        fridge = {'tomato': 2, 'onion': 3, 'olives': 1};
        ```
      - Return `true` if the chef is able to cook the given meal.
    - For example, if you write your function in JavaScript, it would look something like this:
      ```js
      function validateRecipeWithQuantity(fridge, ingredients) {
        // complete this function
      }
      ```

1. Write your code, in the language of your choice, inside a file with the name `problem2-solution-[firstname]-[lastname].[ext]` where:
    - `[firstname]` is your first name spelled the same as you wrote it in the application form.
    - `[lastname]` is your last name spelled the same as you wrote it in the application form.
    - `[ext]` is the extension of the programming language you're using, such as `js`,`ts`,`go`,`c`,`cpp`, `py`, `rb`, etc.
    
    For example, if you wrote your solution in JavaScript and your name is "Sara Al-Tamawi", you should write your code in a file with the name `problem2-solution-sara-al-tamawi.js`.

1. Store the value returned by `validateRecipeWithQuantity` function, and print it out to the screen (i.e. `console.log()` in JS).

### Optional Extra Credit

If you found it easy to solve the problem above, you can claim some extra credit by doing the following. Note that these are all **optional**. You should still submit your solution if you can't do any of these extra requirements.

1. Make your program read the input from command line arguments, STDIN, and/or a JSON file with the name `inputs.json`.
1. Submit a second file with the name `run.sh` which uses `bash` scripting to run your solution file. For example, if your solution is written in javascript, the bash script content might look like this:

    ```bash
    node problem2-solution-sara-al-tamawi.js
    ```
1. Write automated unit tests for your function.
