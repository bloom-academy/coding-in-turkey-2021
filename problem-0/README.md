# Problem 0: Where Is My Food?

After coming back from a long run, you go immediately to your fridge searching for a banana (since it's a good fruit to eat after running). But your fridge is very messy and has many other fruits, vegetables and frozen foods.

You get frustrated because this isn't your first time searching for something inside your messy fridge. So you decide to solve this problem once and for all by writing a function that helps you locate items in your fridge.

## What to submit

1. A function with the name `whereIsMyFood`.
    - Your function must:
      - Receive two variables:
        - `fridge`: is a string array containing all items currently available in your fridge.
        - `item`: is a string of the item you're searching for in the fridges.
      - Return the position of the `item` in `fridge` if it exists, or `-1` if it doesn't.
    - You **MAY NOT** solve this problem by using any array library functions like `find()` or `search()` or `indexOf()`. You must implement the solution yourself using a for or while loop.
    - For example, if you write your function in JavaScript, it would look something like this:

      ```js
      function whereIsMyFood(fridge, item) {
        // complete this function
      }
      ```

1. Write your code, in the language of your choice, inside a file with the name `problem0-solution-[firstname]-[lastname].[ext]` where:
    - `[firstname]` is your first name spelled the same as you wrote it in the application form.
    - `[lastname]` is your last name spelled the same as you wrote it in the application form.
    - `[ext]` is the extension of the programming language you're using, such as `js`,`ts`,`go`,`c`,`cpp`, `py`, `rb`, etc.
    
    For example, if you wrote your solution in JavaScript and your name is "Sara Al-Tamawi", you should write your code in a file with the name `problem0-solution-sara-al-tamawi.js`.

1. Store the value returned by `whereIsMyFood` function, and print it out to the screen (i.e. `console.log()` in JS).

### Optional Extra Credit

If you found it easy to solve the problem above, you can claim some extra credit by doing the following. Note that these are all **optional**. You should still submit your solution if you can't do any of these extra requirements.

1. Make your program read the input from command line arguments, STDIN, and/or a JSON file with the name `inputs.json`.
1. Submit a second file with the name `run.sh` which uses `bash` scripting to run your solution file. For example, if your solution is written in javascript, the bash script content might look like this:

    ```bash
    node problem0-solution-sara-al-tamawi.js
    ```
1. Write automated unit tests for your function.
