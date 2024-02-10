## event
==> An action that occurs as per the user's instruction as input and gives the output in response.

1. onevent="value"
    - example: onclick, onblur, onmouseenter, etc.


### onclick handler
- option 1: directly set on the html element
- option 2: add click function directly --> (funtion call)

- option 3: another --> using selector then add onclick function(reference)

    - if we call then function then it execute before click on it
    - we use reference so that it works after clicking

- option 4: addEventListener('click', function_reference);
    - if we call then function will execute automatically

- option 4(another): addEventListener('click', write a function);