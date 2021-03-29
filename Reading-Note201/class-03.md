# HTML Lists, CSS Boxes, JS Control Flow

From **DUCKETT HTML BOOK**, I learned that during creating a web page, there are in some parts on the page ,we may use the lists to arrange the information within it and in the HTML there are three types of the list that can be used and it can be nested inside one another, like :

> * Ordered lists : these lists are used where each item inside it is numbered .
>
>> `<ol>`
>>
>> `<li>item1</li>`
>>
>> `<li>item2</li>`
>>
>> `<li>item3</li>`
>>
>> `<li>item4</li>`
>>
>> `<li>item5</li>`
>>
>>`</ol>`
>
>
> * Unordered lists : these lists are used where each item it is not numbered .
>
>> `<ul>`
>>
>>`<li>item1</li>`
>>
>>`<li>item2</li>`
>>
>>`<li>item3</li>`
>>
>>`<li>item4</li>`
>>
>>`<li>item5</li>`
>>
>>`</ul>`
>
>
* Definition lists : are made up of a set of terms along with the definitions for each of those terms.
>
>>`<dl>`
>>`<dt>term1</dt>`
>>`<dd>defenitions</dd>`
>>`<dt>term2</dt>`
>>`<dd>defenetions</dd>`
>>`</d>`
>

Also, I got familiar with the boxes and saw how CSS treats each HTML element as if it lives in its own box.these treatments are like a control the dimensions of your boxes ,create borders around boxes,set margins and padding for boxes and show and hide boxes.

From **DUCKETT JS BOOK**, I familiar with array which is a  special type of variable and It stores a list of values, these values are separated by commas.It is important to know that the index of the items inside an array are numbering from zero (not one).Also, You can access the value inside the array and change it's value .the following code show declration statement of an array and it's access statement:
>
>>`// Create the array`
>>
>>`var colors = ['white','black' ,'custom'];`
>>
>>`//update-array`
>>
>>`colors[2] = 'beige'` ;
>
Data types in JavaScript can be coerced from one type to another and all it's value evaluate to either truthy or falsy.This language includes the condition & switch statements that change the flow of the running code,such as :
>
>>* **IF....else statement** : this statement checks a condition . if it resolves to true ,the first code
>> block is executed . and if the condition resolves to false ,the second code block is run instead .
>>
>>`if (condition) {`
>>
>>`//  block of code to be executed if the condition is true`
>>
>>`} else {`
>>`//  block of code to be executed if the condition is false`
>>`}`
>>
>>* **A switch statement**: starts with a variable called the switch value. Each case indicates a possible
>> value for this variable and the code that should run if the variable matches that value.
>>>
>>>`switch(expression) {`
>>>
>>> `case x:`
>>>
>>> `// code block`
>>>
>>> `break;`
>>>
>>> `case y:`
>>>
>>> `// code block`
>>> `break;`
>>>
>>> `default:`
>>>
>>> `// code block`
>>>
>>>`}`
>>
>>* **Loops Statements** : these statements can execute a block of code a number of times.
>>>
>>>`for (statement 1; statement 2; statement 3) {`
>>>
>>> `// code block to be executed`
>>>
>>>`}`
>>>
>>**Where :**
>>Statement 1 is executed (one time) before the execution of the code block.
>>
>>Statement 2 defines the condition for executing the code block.
>>
>>Statement 3 is executed (every time) after the code block has been executed.
