# JS Object Literals; The DOM

>Objects in JS consist of properties and methods. Properties are key value pairs that describe the object. Methods are tasks performed on that object. Objects can be created using literal notation.
>
>>JavaScript
>>var student = {
>> firstExam: 25,
>> secondExam: 27,
>> finalExam: 39,
>> sum: function(){
>> return this.firstExam + this.secondExam + this.finalExam;
>> }
>>};
>
>Objects can be accessed using dot notation
>
>>JavaScript
>>var totalGrade = student.sum();
>>
>
>or using square bracket syntax
>>
>>JavaScript
>>var studentFirstExam = student['firstExam'];
>>
>
>## Document Object Model (DOM)
>
>The DOM specifies how JavaScript can access and amend web page contents while it is in the browser window. The DOM tree is a model of a web page which is stored in the browser memory. It is made up of four types of nodes:
>
>>- The document node
>>- Element nodes
>>- Attribute nodes
>>- Text nodes
>
>To access an individual element node, the following methods are used:
>>
>>- ```getElementByld()```
>>
>>- ```querySelector()```
>
>To access multiple elements or nodelists:
>
>>- ```getElementsByClassName()```
>>
>>- ```getElementsByTagName()```
>>
>>- ```querySelectorAll()```
>
>To move from an element node to a related element node:
>>
>>- ```parentNode```
>>
>>- ```previousSibling``` or ```nextSibling```
>>
>>- ```firstChild``` or ```lastChild```
>
>```nodeValue``` property is used to access or update text nodes, while ```innerHTML``` property accesses the child element and the text. To access the text only, the ```textContent``` property is used. To create element or text nodes the methods ```createElement()``` and ```createTextNode()``` are used. To add or remove nodes from a DOM tree use the methods ```appendChild()``` and ```removeChild()```. This is called DOM manipulation. To access or update attribute values the following methods are used:
>
>>- ```hasAttribute()```
>>
>>- ```getAttribute()```
>>
>>- ```setAttribute()```
>>
>>- ```removeAttribute()```
>
>To cache DOM queries, data is stored in a variable
>
>>```JavaScript
>>var firstItem = getElementById('one');
>>```
>
>To select an element from a nodelist the ```item()``` method or array syntax can be used, although the latter is preferred for being faster.
>
>Moving from one node to another can be difficult due to some browsers adding text nodes for every whitespace between elements. Using jQuery solves this problem.
>
>Using ```innerHTML``` to update the page is risk for Cross-Site Scripting Attacks (XSS), where attackers can access DOM, website cookies, and user accounts. To prevent these attacks the input to database and web servers must be validated. As the data is retrieved from servers all dangerous characters must be escaped so that untrusted sources are not able to modify the script and gain access to important information.
