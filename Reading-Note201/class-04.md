# Read: 04 - HTML Links, CSS Layout, JS Function

## HTML Links

From **DUCKETT HTML BOOK**, I learned that the links in **HTML** are created using this tag ```<a>```. The content that the user clicks on is placed between the opening tag ```<a>``` and the closing tag ```</a>```. The linked page is specified using ```href``` attribute. With large websites, it is preferred to place the related pages in directories. To link to other pages on the same website relative links are used.
.Also,Email links that launch the user email program can be created using ```mailto``` property.
>
>>```HTML
>><a href="mailto:user@example.org">Email User</a>
>>```
>
In addition,to open links in a new window, use the target attribute with value ```_blank``` in the opening anchor tag.
>
>>```HTML
>><a href="http://www.imdb.com" target="_blank">
>>```
>
Links to specific parts on the same page are created using id attribute for specifying the section and hash symbol with the id in the href attribute.Also , I learned that each element in CSS is placed in its own box either block-level box or an inline box. To separate boxes, borders, margins, padding, and background colors are used. The positioning schemes in CSS allow controlling the page layout. Positioning schemes are specified using the ```position``` property with different values such as static, relative, absolute, and fixed.
>
>>- In static or normal flow positioning, each block-level element is above the next one which is the default >>positioning.
>>
>>- Relative positioning moves the element relative to its original position in normal flow.
>>
>>- Absolute positioning takes the box out of normal flow, in which case the box acts like it is not on the    page. The offset properties specify where the element should appear relative to its containing element.
>>
>>- In fixed positioning, the element stays in the same place even if the user scrolls down the page.
>
>To control which box stays on top in case of overlapping, the ```z-index``` property is used.
>
>The design of a webpage must adapt to different screen resolutions. Fixed width layouts do change size along with the browser window. In this layout the designer has more control over the appearance, but for users with different screen sizes the design will not work well.
On the other hand, liquid layouts adapt to the browser size, but the page might not look as the designer intended.
>
>From **DUCKETT JS BOOK**, I got familiar with  JS function ,which is a series of statements grouped together to perform a specific task. The function name should indicate that task, which is important to **call** the function and execute it. The pieces of information passed to a function are called **parameters**. If the function is expected to yield an answer the result is called the **return value**.
>
>Example of declaring a function:
>>
>>```JavaScript
>> function sayHello(){
>>    document.write('Hello');
>> }
>>
>> ```
>
>To call this function the following statement is used
>>
>>```JavaScript
>>sayHello();
>>```
>
>After the function is executed the code continues to run from where it was called. Functions can also take certain number of parameters, so when calling the function certain arguments, being either values or variables, are passed. To get a single value out of a function we use the return statement.
>
>>```JavaScript
>>function getArea(width, height){
>>    return width * height;
>>}
>>```
>>
>>```JavaScript
>>getArea(2, 3);
>>```
>
>From the article I knew that there are two roles in pair programming; the driver and the navigator. The **driver** is associated with writing the program, while the navigator thinks about how an algorithm is represented as code. **Pair programming** improves the ability to explain the purpose of the code, listen to others, read code written by others, and write code on their own. This leads to higher efficiency, improved social skills, and work environment readiness.
