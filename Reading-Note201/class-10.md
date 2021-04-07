# JS Debugging

Learning JS debugging involves several concepts such as order of execution, execution contexts, variable scope and hoisting. Sometimes tasks cannot complete until another statement or function has been executed. Variable scope explains that if a variable is declared outside a function, it can be used anywhere because it has global scope. When a variable is declared inside a function, it can only be accessed inside that function because it has function-level scope. Hoisting explains that functions can be called before they are declared given they are created using function declaration. The ```Error``` object has four properties; ```name```, ```message```, ```fileNumber```, and ```lineNumber```. There are seven types of built-in errors in JavaScript:

>- ```Error```: this is a generic object from which all other error objects are created.
>- ```SyntaxError```: syntax is not correct.
>- ```ReferenceError```: variable does not exist.
>- ```TypeError```: unexpected data type that
cannot be coerced such as ```Document.write('hello)```.
>- ```RangeError```: numbers not in acceptable range.
>- ```URIError```: incorrect use of URI functions where some characters are not escaped.
>- ```EvalError```: ```eval()``` function used incorrectly.

There are two ways to deal with errors; debugging using developer tools, or handling errors gracefully using ```try```, ```catch```, and ```finally``` statements. Data can be logged to the console using ```console.log()``` method. For grouping data written to the console, ```.group()``` and ```.groupEnd()``` methods are used.

Breakpoints can be inserted using ```debugger``` keyword to pause the execution of a script on a certain line.

```try``` statement includes the code that might raise an exception. ```catch``` block of code runs only if ```try``` code block raises an exception. ```finally``` block of code will run whether an exception was thrown or not. ```throw``` statement is used for throwing errors in cases where data comes from a third party.

Some debugging tips are:

>- Trying another browser as some problems relate to a specific browser.
>- Removing parts of code to track down source of problem.
>- Explaining the code.
>- Searching online
>- Validation tools

To avoid some common errors:

>- Check variable names and scopes; names are case sensitive, and reserved words are not used as variable names.
>- Check for missing or extra characters (braces, parentheses, or commas)
>- Make sure id attributes are unique in HTML
>- Use ```==``` for comparison not the assignment operator ```=```
>- Check the value type inside a ```switch``` statement as they are not coerced.
