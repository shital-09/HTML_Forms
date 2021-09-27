# HTML Form

An HTML form is a section of a document that contains controls such as text fields, password fields, checkboxes, radio buttons, submit buttons, menus, etc.
An HTML form facilitates the user to enter data that is to be sent to the server for processing such as name, email address, password, phone number, etc..

## Why use HTML Form

HTML forms are required if you want to collect some data from the site visitor.
For example: If a user wants to purchase some items on the internet, he/she must fill the form such as shipping address and credit/debit card details so that item can be sent to the given address.

## HTML Form Tags
Let's see the list of HTML 5 form tags.

![App Screenshot](https://codebridgeplus.com/wp-content/uploads/html-form.jpg)

## HTML form element
The HTML form element provide a document section to take input from user. It provides various interactive controls for submitting information to web server such as text field, text area, password field, etc.
The form element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc

```bash
<form>  
//Form elements  
</form>
```

## The input Element

The HTML input element is the most used form element.
An input element can be displayed in many ways, depending on the type attribute.
Here are some examples:

```bash
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

```bash
<!DOCTYPE html>
<html>
<body>
<form>  
  First Name: <input type="text" name="firstname"/> <br/>  
  Last Name:  <input type="text" name="lastname"/> <br/>  
</form>
</body>
</html> 
```

![App Screenshot](https://static.javatpoint.com/htmlpages/images/html-textfield-control.png)

## HTML textarea tag in form

The textarea tag in HTML is used to insert multiple-line text in a form. The size of textarea can be specify either using "rows" or "cols" attribute or by CSS.

```bash
<!DOCTYPE html>  
<html>    
<body>  
  <form>  
        Enter your address:<br>  
      <textarea rows="2" cols="20"></textarea>  
  </form>  
</body>  
</html>
```

![App Screenshot](https://static.javatpoint.com/htmlpages/images/html-textarea-tag-in-form.png)

## The label Element

The label tag defines a label for many form elements.
The label element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

## Radio Button Control

The radio button is used to select one option from multiple options. It is used for selection of gender, quiz questions etc.
If you use one name for all the radio buttons, only one radio button can be selected at a time.

![App Screenshot](https://res.cloudinary.com/practicaldev/image/fetch/s--m5WmQIUZ--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://dev-to-uploads.s3.amazonaws.com/i/c260ismydk1rj54ykvpt.png)

## Checkbox Control
The checkbox control is used to check multiple options from given checkboxes

![App Screenshot](https://i.stack.imgur.com/xSqEw.jpg)

## Submit button control

HTML input type="submit" are used to add a submit button on web page. When user clicks on submit button, then form get submit to the server.

![App Screenshot](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQRP8DuEd20dJHNsEKtF7VOK0Ot9PoHmrhGh-yHwpdMnUqMjwk1nB-avhqM6wGu5p3sJnM&usqp=CAU)


## HTML Password Field Control

The password is not visible to the user in password field control.

![App Screenshot](https://i.stack.imgur.com/Po7JT.jpg)

## HTML 5 Email Field Control

The email field in new in HTML 5. It validates the text for correct email address. You must use @ and . in this field.
![App Screenshot](https://static.javatpoint.com/htmlpages/images/html-5-email-field-control2.png)

## HTML fieldset element:

The fieldset element in HTML is used to group the related information of a form. This element is used with <legend> element which provide caption for the grouped elements.

![App Screenshot](https://docs.webix.com/media/desktop/form_fieldset.png)

## HTML Form Example
Following is the example for a simple form of registration.

```bash
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