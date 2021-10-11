# Problem 3: Fridge Website

Now we have a website showing the items in our fridge. There are two missing functionalities from this fridge that you need to complete:

### Adding Items
We need to make the "Add" function work with the textbox such that the user can insert new items to the fridge. Each item will be added as two words separated by space (`itemName` `count`). For example, entering "Lettuce 3" will insert a new item to the fridge called `Lettuce` and its count in the table will be shown as `3`.

*Note:* consider adding error handling in case the entered text isn't a valid item.

### Removing Items
Some code is already provided to you that invokes the `remove()` function when the "X" button is clicked to remove an item. Removing an item must be done by manipulating the CSS of the page to hide the removed item. In other words, you *MAY NOT* use `removeChild()` function or anything else that actually deletes the HTML element/node. We simply want to hide the removed item using CSS.
