# Forms and Events

## HTML Forms

Forms are used to retrieve input from users. There are multiple types of input controls such as text input, radio buttons, and file upload. To differentiate between different input data, the information is sent using name value pairs.

Forms are created using ```<form>``` element with with required ```action``` that specifies the URL for the page which will receive form information. The ```<input>``` is used to create form controls with type attribute specifying the kind of information to submit.

- For text input:

```HTML
<input type="text" name="username" maxlength="30" />
```

- For textarea:

```HTML
<textarea name="comments" cols="22" rows="6">Comment here</textarea>
```

- For Radio buttons:

```HTML
<input type="radio" name="Season" value="fall"
checked="checked" /> Fall
```

- For drop down lists:

```HTML
<select name="OS">
<option value="windows">Windows</option>
<option value="linux">Linux</option>
<option value="macOS">macOS</option>
</select>
```

- For file input:

```HTML
<input type="file" name="resume" /><br />
<input type="submit" value="Upload" />
```

- For search input:

```HTML
<input type="search" name="search" />
<input type="submit" value="Search" />
```

Related form elements can be grouped using ```<fieldset>``` element with a child ```<legend>``` element which explains the purpose of the form control group. 

## CSS Lists, Tables and Forms

To change the style of bullet points of a list use the ```list-style-type``` property. It can different values such as ```none```, ```disc```, ```circle```, ```square```, ```decimal```, l```ower-alpha```, and ```lower-roman```.

```list-style-position``` property takes two values. A value of ```outside``` indicates that bullet points sit to the left of text blocks which is the default. A value of ```inside``` means that bullet points sit inside the text blocks.

Tables can be styled using different properties such as ```width```, ```padding```, ```text-transform```, ```letter-spacing```, ```border-spacing```, ```border-collapse``` ```font-size```, ```border-top```, ```border-bottom```, ```text-align```, and ```:hover```.

Styling text input can be done using common text styling properties. The text input can change color when it is being used by adding the ```:focus``` pseudo-class.

## JS Events

Events occur when the user interacts with the web page (clicking on a link, hovering over an element, or resizing the window). The preferred way to bind an event to an element is using DOM level 2 event listeners. Event listeners can handle multiple functions at a time. The binding syntax using an event listener:

```JavaScript
element.addEventlistener('event', functionName [, Boolean]);
```

where ```element``` and ```'event``` are the element and the event to be bound. ```functionName``` is the function to be called. ```[, Boolean]``` indicates the event flow, usually set to false. When there are arguments to be passed to the function, it is wrapped in an anonymous function to prevent the function code from running immediately.

When the code has event listeners on an element and one of its ancestors or descendants, event flow has to be considered.  The default value of event flow is false or bubbling phase, which means that events start at the most specific node and flow outward to the least specific node.