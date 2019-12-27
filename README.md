Working through jQuery via FreeCodeCamp resources and copying passed code to Git repo as I go through each task. Documenting below anything new I learn.

- Created a doucment ready function. Lives inside html script tags and executes after page is loaded:

```
$(document).ready(function(){

  });
```

- Learned how to target HTML elements with jQuery. Can work as follows:

    - Selectors: Takes the the element based on its selector name and executes subsequent code on all elements of that selector. Example:

    ```
    $("p").addClass("red-text");
    ```

    Would give all paragraph elements a class of "red-text" which, presumably, would draw the CSS for that class to make text red.

    - Class: Takes the the element based on its class name and executes subsequent code on all elements with that class. Example:

    ```
    $(".well").addClass("animated shake")
    ```

    Would apply additional classes of "animated" and "shake" to all elements currently containing the class "well". Note requires a period before class name, as in CSS.

    - ID: Takes the the element based on its id and executes subsequent code on all elements with that id. Example:

    ```
    $("#target3").addClass("animated fadeOut")
    ```

    Would apply classes of "animated" and "fadeOut" to the element with id "target3". Note requires a hash before class name, as in CSS.