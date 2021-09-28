# HTML Form

An HTML form is a section of a document that contains controls such as text fields, password fields, checkboxes, radio buttons, submit buttons, menus, etc.
An HTML form facilitates the user to enter data that is to be sent to the server for processing such as name, email address, password, phone number, etc..

## Why use HTML Form

HTML forms are required if you want to collect some data from the site visitor.
For example: If a user wants to purchase some items on the internet, he/she must fill the form such as shipping address and credit/debit card details so that item can be sent to the given address.

## HTML Form Tags
Let's see the list of HTML 5 form tags.

![App Screenshot](https://codebridgeplus.com/wp-content/uploads/html-form.jpg)

`NOTE:` The \<form> element does not itself create a form but it is container to contain all required form elements, such as \<input>, \<label>, etc.

## HTML  \<form> element 
The HTML \<form> element provide a document section to take input from user. It provides various interactive controls for submitting information to web server such as text field, text area, password field, etc.
The \<form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc

```HTML
<form>  
//Form elements  
</form>
```

## The \<input> Element

The HTML \<input> element is the most used form element.
An input element can be displayed in many ways, depending on the type attribute.
Here are some examples:

```HTML
<!DOCTYPE html>
<html>
<body>
<form>
  <label for="fname">Name:</label><br>
  <input type="text" id="fname" name="fname"><br>
</form> 
</body>
</html> 
```
![App Screenshot](https://www.w3jar.com/wp-content/uploads/input-type-text.png)

## HTML TextField Control

The type="text" attribute of input tag creates textfield control also known as single line textfield control.

```HTML
<!DOCTYPE html>
<html>
<h3>Example Of Text Field</h3>
<body>
    <form>
        <label for="EMAIL ID">Email Id:</label><br>
        <input type="text" name="Email id" id="Email id">
    </form>
</body>
</html>
```

![App Screenshot](https://media.geeksforgeeks.org/wp-content/uploads/Screen-Shot-2017-12-13-at-10.03.09-PM.png)

## HTML \<textarea> tag in form

The <\textarea> tag in HTML is used to insert multiple-line text in a form. The size of textarea can be specify either using "rows" or "cols" attribute or by CSS.

```HTML
<!DOCTYPE html>
<html>
<h3>Example of a Text Area Box</h3>
<body>
    <form>
        <label for="Description">Description:</label>
        <textarea rows="5" cols="50" name="Description"
                            id="Description"></textarea>
    </form>
</body>
</html>
```

![App Screenshot](https://media.geeksforgeeks.org/wp-content/uploads/Screen-Shot-2017-12-14-at-2.52.37-AM.png)

## The \<label> Element

The \<label> tag defines a label for many form elements.
The \<label>element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

## Radio Button Control

The radio button is used to select one option from multiple options. It is used for selection of gender, quiz questions etc.
If you use one name for all the radio buttons, only one radio button can be selected at a time.

```HTML
<!DOCTYPE html>
<html>
<h3>Example of Radio Buttons</h3>
<body>
    <form>
        SELECT GENDER
        <br>
        <input type="radio" name="gender" id="male">
        <label for="male">Male</label><br>
        <input type="radio" name="gender" id="female">
        <label for="female">Female</label>
    </form>
</body>
</html>
```

![App Screenshot](https://media.geeksforgeeks.org/wp-content/uploads/Screen-Shot-2017-12-14-at-3.08.52-AM.png)

## Checkbox Control
The checkbox control is used to check multiple options from given checkboxes

```HTML
<!DOCTYPE html>
<html>
<h3>Example of HTML Checkboxes</h3>
<body>
    <form>
        <b>SELECT SUBJECTS</b>
        <br>
        <input type="checkbox" name="subject" id="maths">
        <label for="maths">Maths</label>
        <input type="checkbox" name="subject" id="science">
        <label for="science">Science</label>
        <input type="checkbox" name="subject" id="english">
        <label for="english">English</label>
    </form>
</body>
</html>
```

![App Screenshot](https://media.geeksforgeeks.org/wp-content/uploads/Screen-Shot-2017-12-13-at-10.22.57-PM.png)

## Submit and Reset button control

HTML input type="submit" are used to add a submit button on web page. When user clicks on submit button, then form get submit to the server. The Reset Button is used to reset the form data and use the default values.

```HTML
<!DOCTYPE html>
<html>
<h3>Example of a Submit And Reset Button</h3>
<body>
    <form action="test.php" method="post" id="users">
        <label for="username">Username:</label>
        <input type="text" name="username" id="Username">
        <input type="submit" value="Submit">
        <input type="reset" value="Reset">
    </form>
</body>
</html>
```

![App Screenshot](https://media.geeksforgeeks.org/wp-content/uploads/Screen-Shot-2017-12-14-at-3.05.00-AM.png)


## HTML Password Field Control

The password is not visible to the user in password field control.

```HTML

<!DOCTYPE html>
<html>
<h3>Example of Password Field</h3>   
<body>
    <form>
        <label for="user-password">Password:
        </label><br>
        <input type="password" name="user-pwd"id="user-password">
    </form>
</body>
</html>
```

![App Screenshot](https://media.geeksforgeeks.org/wp-content/uploads/Screen-Shot-2017-12-13-at-10.10.26-PM.png)

## HTML 5 Email Field Control

The email field in new in HTML 5. It validates the text for correct email address. You must use @ and . in this field.

![App Screenshot](https://mailtrap.io/wp-content/uploads/2020/05/html5_email_validation4.png)

## HTML \<fieldset> element:

The \<fieldset> element in HTML is used to group the related information of a form. This element is used with <legend> element which provide caption for the grouped elements.

![App Screenshot](https://docs.webix.com/media/desktop/form_fieldset.png)

## HTML Form Example
Following is the example for a simple form of registration.

```HTML
<!DOCTYPE html>  
 <html>  
 <head>  
  <title>Form in HTML</title>  
</head>  
 <body>  
     <h2>Registration form</h2>  
    <form>  
     <fieldset>  
        <legend>User personal information</legend>  
        <label>Enter your full name</label><br>  
        <input type="text" name="name"><br>  
         <label>Enter your email</label><br>  
         <input type="email" name="email"><br>  
         <label>Enter your password</label><br>  
         <input type="password" name="pass"><br>  
         <label>confirm your password</label><br>  
         <input type="password" name="pass"><br>  
         <br><label>Enter your gender</label><br>  
         <input type="radio" id="gender" name="gender" value="male"/>Male  <br>  
         <input type="radio" id="gender" name="gender" value="female"/>Female <br/>    
         <input type="radio" id="gender" name="gender" value="others"/>others <br/>   
          <br>Enter your Address:<br>  
         <textarea></textarea><br>  
         <input type="submit" value="sign-up">  
     </fieldset>  
  </form>  
 </body>  
</html>  

```
![App Screenshot](https://static.javatpoint.com/htmlpages/images/html-form-example.png)

#### Reference links:
- https://www.w3schools.com/html/html_forms.asp
- https://www.javatpoint.com/html-form
- https://www.geeksforgeeks.org/html-design-form/

## Contributed by Shital Punde
