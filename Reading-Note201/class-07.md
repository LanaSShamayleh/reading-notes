# HTML Tables; JS Constructor Functions

>## HTML Tables

Tables are information represented in a grid. Tables in HTML are inserted row by row. The ```<table>``` element is used to create a table. The child element table row ```<tr>``` indicates the start of each row. Inside each table row there is table data element ```<td>``` which represents a table cell. To create a table heading for either a column or a row the ```<th>``` is used with scope attribute being either ```col``` or ```row```. To make the table cell span multiple columns use the ```colspan``` attribute with value of the number of columns. Similarly, the ```rowspan``` attribute is used for spanning multiple rows. For long tables, three elements are used to differentiate between the main content and the first and the last rows; ```<thead>```, ```<tbody>```, and ```<tfoot>```.

>## JS Constructor Functions

To create an object using constructor functions, the new keyword and Object() constructor function are used.

>>```JavaScript
>>var student = new Object();
>>student.firstExam = 25,
>>student.secondExam = 27,
>>student.finalExam = 39,
>>student.sum = function(){
>>        return this.firstExam + this.secondExam + this.finalExam;
>>};
>>```

Multiple objects having the same property keys can be created using constructor notation.

>>```JavaScript
>>function Student(firstExam, secondExam, finalExam){
>>    this.firstExam = firstExam;
>>    this.secondExam = secondExam;
>>    this.finalExam = finalExam;
>>}

>>Student.prototype.sum = function(firstExam, secondExam, finalExam){
>> this.total = this.firstExam + this.secondExam + this.finalExam;
>>}```

Using the new keyword and the name of the function creates a new instance of the object.

>>```JavaScript
>>var studentA = new Student(24, 29, 36);
>>var studentB = new Student(22, 30, 38);
>>```

New properties can be added to objects using dot notation or array syntax. To delete properties use the ```delete``` keyword.

>>Arrays are objects where the key for each value is its index.
>>
>>There are there groups of built-in objects:
>>
>>- Browser Object Model which represents the current browser window.
>>
>>- Document Object Model which is a model of the current webpage
>>
>>- Global JavaScript objects which are groups of objects pertaining to different parts of the JS language.

An example of global objects is Date object. An instance of the date object can be created
>>
>>```JavaScript
>>var today = new Date();
>>```
>>
There are several methods used with Date object such as ```setDate()```, ```setFullYear()```, ```setMonth()```, ```setHours()```, and ```setMinutes()```.

To specify the date and time using the Date object as the following formats:

>>- YYYY, MM, DD, HH, MM, SS
>>
>>- MMM DD, YYYY HH:MM:SS
>>
>>```JavaScript
>>var birthDate = new Date('1997, 11, 17, 19, 45, 00');
>>var birthDate = new Date('Nov 17, 1997 19:45:00');
>>```
