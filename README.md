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
<!--<form>
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
</form> -->

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

15)font-family: FAMILY_NAME, GENERIC_NAME;.
The GENERIC_NAME is optional, and is a fallback font in case the other specified font is not available. This is covered in the next challenge.
Family names are case-sensitive and need to be wrapped in quotes if there is a space in the name. For example, you need quotes to use the "Open Sans" font, but not to use the Lobster font. Generic font family names are not case-sensitive. Also, they do not need quotes because they are CSS keywords.

16) CSS borders have properties like style, color,radius and width.

17) border-radius of 50% makes the image have circular border.

18) id attributes should be unique. Browsers won't enforce this, but it is a widely agreed upon best practice. So please don't give more than one element the same id attribute

19) id is not reusable and should only be applied to one element. An id also has a higher specificity (importance) than a class so if both are applied to the same element and have conflicting styles, the styles of the id will be applied.

20) em is based on the size of an element's font. If you use it to set the font-size property itself, it's relative to the parent's font-size.

21) you can style your body element just like any other HTML element, and all your other elements will inherit your body element's styles.

23) It doesn't matter which order the classes are listed in the HTML element. However, the order of the class declarations in the <style> section are what is important. The class declared last overrides the style properties of the class declared before that.
  
24) if the id and class having same property are applied, id is preferred EVEN IF THE CLASS IS DECLARED AFTER IT.

25) inline styling > id > class. inline overrides all CSS declarations in the style element.

26) Add the keyword !important to your pink-text element's color declaration to make 100% sure that your h1 element will be pink. ex: color: pink !important; 
    This is the most powerful and has the highest preference when compared to the other types.
    !important > inline styling > id > class

27) [type:'radio']{   //helps the spacing around the radio button. only margin is used not padding.
      margin: 20px 10px 30px 40px;   
    }
   
28) --penguin-skin: gray;  #This will create a variable named --penguin-skin and assign it the value of gray.

29) After you create your variable, you can assign its value to other CSS properties by referencing the name you gave it.
    background: var(--penguin-skin);
This will change the background of whatever element you are targeting to gray because that is the value of the --penguin-skin variable.

30) background: var(--penguin-skin, black); #black is the fallback value if the variable --penguin-skin wasnt located.
the variable can only be used inside the class where it is declared. To avoid this, the variables are declared inside the 
:root{     //this is like the container of all the html. like the html tag.
} 
31) media query are used to apply certain changes at a particular size
@media(max-size:40px){
  :root{
    variable : black;
  }
}
31) Another declaration of colors can be added to make up for the browser compatibility issues with the code.

32) In web development, HTML gives structure and semantics to a page's content, and CSS controls the layout and appearance of it.

33) text-align: justify; causes all lines of text except the last line to meet the left and right edges of the line box.

text-align: center; centers the text

text-align: right; right-aligns the text

And text-align: left; (the default) left-aligns the text.

34)  With the strong tag, the browser applies the CSS of font-weight: bold; to the element.4

35) Try to avoid using the u tag when it could be confused for a link. Anchor tags also have a default underlined formatting.

36) height, width.

37) <strong></strong>    -> font-weight:bold;
    <u></u>              -> text-decoration:underline;
    <em></em>            -> font-style:italic;
    <s></s>              -> text-decoration:line-through;
    <hr>                 -> used to add a horizontal line across the width of the containing element.
    
38) rgba() is added to the background-color
    hex is added to the color
    
39) he box-shadow property takes values for offset-x (how far to push the shadow horizontally from the element), offset-y (how far to push the shadow vertically from the element), blur-radius, spread-radius and a color value, in that order. The blur-radius and spread-radius values are optional.
    box-shadow: 0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23); #multiple shadows are present.

40) The opacity property in CSS is used to adjust the opacity, or conversely, the transparency for an item.

    A value of 1 is opaque, which isn't transparent at all.
    A value of 0.5 is half see-through.
    A value of 0 is completely transparent.
    
41) text-transform: uppercase;
    text-transform: lowercase;
    text-transform: initial;
    text-transform: capitalize;
    text-transform: inherit;
    text-transform: none;
    
 42) CSS offers the line-height property to change the height of each line in a block of text. As the name suggests, it changes the amount of vertical space that each line of text gets.
