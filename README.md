Working through jQuery via FreeCodeCamp resources and copying passed code to Git repo as I go through each task. Documenting below anything new I learn.

- Created a doucment ready function. Lives inside html script tags and executes after page is loaded:

```
$(document).ready(function(){

  });
```

- Learned how to target HTML elements with jQuery and manipulate them accordingly. Can work as follows:

    - Selectors: Takes the the element based on its selector name and executes subsequent code on all elements of that selector. Example:

    ```
    $("p").addClass("red-text");
    ```

    Would give all paragraph elements a class of "red-text" which, presumably, would draw the CSS for that class to make text red.

    - Class: Takes the the element based on its class name and executes subsequent code on all elements with that class. Example:

    ```
    $(".well").css("color","blue");
    ```

    Would change text color of all elements currently containing the class "well" to blue. Note requires a period before class name, as in CSS.

    - ID: Takes the the element based on its id and executes subsequent code on all elements with that id. Example:

    ```
    $("#target3").remove();
    ```

    Would remove the element with id "target3". Note requires a hash before class name, as in CSS.