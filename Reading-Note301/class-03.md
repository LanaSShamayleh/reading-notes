# What does .map() return?

    a new array

## If I want to loop through an array and display each value in JSX, how do I do that in React?

   we using the JavaScript map() function and return a <li> element for each item. then, assigning  the resulting array of elements to listItems

## Each list item needs a unique ____

    Key

## What is the purpose of a key?

    Keys help React identify which items have changed, are added, or are removed

## What is the spread operator?

    JavaScript, spread syntax refers to the use of an ellipsis of three dots (âĶ) to expand an iterable object into the list of arguments.

## List 4 things that the spread operator can do

    1- Copying an array
    2- Concatenating or combining arrays
    3- Using Math functions
    4- Using an array as arguments

## Give an example of using the spread operator to combine two arrays

    const objectOne = {hello: "ðĪŠ"}
    const objectTwo = {world: "ðŧ"}
    const objectThree = {...objectOne, ...objectTwo, laugh: "ð"}
    console.log(objectThree) // Object { hello: "ðĪŠ", world: "ðŧ", laugh: "ð" }
    const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("ð".repeat(5))}}
    objectFour.laugh() // ððððð

## Give an example of using the spread operator to add a new item to an array

    const fewFruit = ['a','b','c']
    const fewMoreFruit = ['d', 'e', ...fewFruit]
    console.log(fewMoreFruit) //  Array(5) [ "d", "e", "a", "b", "c" ]
