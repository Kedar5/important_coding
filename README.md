# important_coding
This repository contains all the important points used in coding in web developement.

1) Web developers traditionally use lorem ipsum text as placeholder text. The 'lorem ipsum' text is randomly scraped from a famous passage by Cicero of Ancient Rome.
Lorem ipsum text has been used as placeholder text by typesetters since the 16th century, and this tradition continues on the web.

2) Comments in HTML starts with <!--, and ends with a -->

3) HTML5 introduces more descriptive HTML tags. These include header, footer, nav, video, article, section and others. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.

4) All img elements must have an alt attribute. The text inside an alt attribute is used for screen readers to improve accessibility and is displayed if the image fails to load.
Note: If the image is purely decorative, using an empty alt attribute is a best practice.

5) The href attribute value with a #, also known as a hash symbol creates a dead link.

6) Text input can be created like this: <input type="text">

7) Placeholder text is what is displayed in your input element before your user has inputted anything.

8) Web forms that actually submit data to a server using nothing more than pure HTML. You can do this by specifying an action on your form element which contains the input tag inside of it.

9) Let's add a submit button to your form. Clicking this button will send the data from your form to the URL you specified with your form's action attribute.

10) Make your text input a required field, so that your user can't submit the form without completing this field.

11) 
<form>
  <label for = "firstname"> First Name
    <input id = "firstname" type="text" placeholder="Enter first name" name="first name">
  </label></br>
  <label for = "lastname"> Last Name
    <input type="text" placeholder="Enter last name" name="last name">
  </label></br>
  <label for = "maleid"> Male
    <input id = "maleid" type="checkbox" value = "male" name="gender"> 
  </label></br>
  <label for = "femaleid"> Female 
    <input type="checkbox" value = "female" name="gender">
  </label></br>
  <label for = "yesid"> Yes
    <input id = "yesid" type="radio" value = "yes" name = "yesorno"> 
  </label></br>
  <label for = "noid"> No
    <input id = "noid" type="radio" value = "no" name = "yesorno">
  </label></br>
  <button type = "submit">Submit</button>
</form>

12)Set the first of your radio buttons and the first of your checkboxes to both be checked by default.
To do this, just add the word "checked" to the inside of an input element. For example:
<input type="radio" name="test-name" checked>

13) At the top of your document, you need to tell the browser which version of HTML your page is using. HTML is an evolving language, and is updated regularly. Most major browsers support the latest specification, which is HTML5. However, older web pages may use previous versions of the language.

You tell the browser this information by adding the <!DOCTYPE ...> tag on the first line, where the "..." part is the version of HTML. For HTML5, you use <!DOCTYPE html>.

<!DOCTYPE html>
<html>
  <!-- Your HTML code goes here -->
</html>

14) Any markup with information about your page would go into the head tag. Then any markup with the content of the page (what displays for a user) would go into the body tag. 
Metadata elements, such as link, meta, title, and style, typically go inside the head element.
<!DOCTYPE html>
<html>
  <head>
    <!-- metadata elements -->
  </head>
  <body>
    <!-- page contents -->
  </body>
</html>
