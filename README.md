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

- In addition to above learned to use other functions such as:
    - removeClass(): Removes class from element.
    - disable(): Element remains visible but is disabled therefore not accessible.
    - html(): Alters html of an element. Text can also be altered at the same time.
    - text(): Alters text of an element without compromising HTML.
    - appendTo(): Takes an element and moves it by appends it to another, e.g. from one div to another.
    - clone(): Creates a copy of the element. Can then be chained to other functions, i.e. appendTo(), in order to do something with the clone.