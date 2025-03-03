# WELCOME TO THE RESUME FILE

This will contain the Overview or Resume of Everything Learned for this Mini Project HTML and CSS wise and will Go Down here for any Specific Remarks regarding HTML or CSS

# HTML :

we have covered HTML elements such as:

<head></head>: where all the links to stylesheet, scripts, meta data, title of the page goes,  realy important element

<h1></h1> : headers and have different importance from 1 to 6 with 1 having the highest importance and can be seen once on the Page
<p><p> : this can be seen in the content of the page
<a></a> : anchor , used for linking into other pages on the internet or liking to other pages in our project

then we started learning about attributes , attributes control the element Behavior, in the <a></a> some important attributes are
... the href=:"" : we need to enter the Path here , linking to either other web pages on the internet or other pages on our project; then we have
... the target=""; helps us to open the linked web page into a new Tab by setting the value for target to "\_blank"
dont' mind the forward slash.

also note the any link to other webpages on the internet are regarded as : Absolute path
and links that links to webpages in our projects are : Relative Paths

<ul></ul>
<ol></ol>, both are list ul is unordered and ol is ordered they need <li></li> to list items or something, goes without saying that li are block level elements

<img/> : img elements are void elements meaning they don't need a closing tag
img helps us insert from our project or link images on other websites to our own . again paths will play a big role here just as in the <a></a> section
we also talked about attributes here , the src attribute help us to have a path linking either to the iamge in our project or to an image in other webpage on the internet
note that it is mandatory to have an alt attribute with an img element it not only improves SEO but helps screen readers , our alt value should reflect our image for better value

<figure></figure>: this element is the parent of img and figcaption . for better html structure and improve SEO as usual , this provides the best combination if we want to use the img element associated with a description 
wich the <figcaption></figcaption> heps with , it helps descriing the img element  and all together it looks somehting like this :
<figure>
    <img/>
    <figcaption>
    </figcaption>
</figure>

<main></main>: this element contains all the content of our webpage and helps with the semantic structure of the page to improve SEO(Search Engine optimization)
after the <body></body>,  we should have the main element to contain all the content of the webpage

<section></section>: again this helps with semantic for the structure and SEO improvement . this is used for containing content of same importance of same sub-subject, it's like chapters in a book, it usually has the h2 as the main heading for the subjection of that content

<form></form>: this element helps with forms we wain't in depth with it yet but so far we that it has a action attribute , which indicates where form data should be sent.
inside the form we have an <input/> which has different options from its type attribute , it can also have several attributes which are , required, checked , name , value , id placeholder and so on...
note that <input/> is a void element

<fieldset</fieldset>: filedset element is like figure but this one contains input and label that are related

<label></label> : label elements are used to help associate the text for an input element
with the input element itself, it has the for attribute that helps associate with the id of the input element

so inside the
<fieldset</fieldset> we will have both <input/>, <label></label> and <legend</legend> is used like figcaption on figure here it's placed first then comes the other two elements note that fieldset are block level elements

<footer></footer>: this is a section of its own , it contains information, contacts and some other stuff regarding the Page

notes:

In order to make a checkbox checked or radio button selected by default,
you need to add the checked attribute to it.

# tips with radio buttons

Notice that both radio buttons can be selected at the same time.
To make it so selecting one radio button automatically deselects the other,
both buttons must have a name attribute with the same value.

form data for selected checkboxes are name / value attribute pairs.
While the value attribute is optional,
it's best practice to include it with any checkboxes or radio buttons
on the page.

# tips with checkboxes

- attributes control elements behavior and are used inside the opening tag of an element

- the Figure element is used to associate the img element the figcaption element, representing the caption of the image or its description

- while dealing with Forms , inputs and anything related to this , For convenience,
  set the button's value attribute to the same value as its id attribute.

- The fieldset element is used to group related inputs and labels together
  in a web form.
  fieldset elements are block-level elements,
  meaning that they appear on a new line.
- The legend element acts as a caption for the content in the fieldset element.
  It gives users context about what they should enter into that part of
  the form.

- There's another way to associate an input element's text
  with the element itself.
  You can nest the text within a label element and add a for attribute
  with the same value as
  the input element's id attribute.

  - In order to make a checkbox checked or radio button selected by default,
    you need to add the checked attribute to it.

- The head element is used to contain metadata about the document,
  such as its title, links to stylesheets, and scripts.
  Metadata is information about the page that isn't displayed
  directly on the page.

- The html element is the root element of an HTML page and wraps
  all content on the page.

- All pages should begin with <!DOCTYPE html>.
  This special string is known as a declaration and ensures the browser
  tries to meet industry-wide specifications.

<!DOCTYPE html> tells browsers that the document is an HTML5 document

which is the latest version of HTML.

# CSS : NO CSS sorry, the Project was HTML only

This will contain the Things that stand out to me during this mini Project

# What stood out to me:

the figure element which contains both img and figcaption elements respectivelly.
the fieldset that contains the input and the label respectivelly as well it's just great to know that this group forms a team to create something related to that thing if that makes any sense at all

the rel tag inside the a element with its values , noopener and noreferrer which provide both privacy and security on links that opens on a new Tab

# Notes and Structure of the Project:

Boilerplate

main element

h1 with text : CatPhotoApp

with sections contaains

h2 with text : Cat Photos, has subject of the first section

including two p elements that nest each an anchor element with absolute paths, then a img element nested into an a element , absolute path here as well

then we have another section
with h2 as its subject with text : Cat Lists
then we have a h3 with text things cats love
then we have an ol with 3 nested li

then we have figure with an img and figcaption nested inside of it

then we have another h3 with text : Top 3 things cats hate
then we have an ol with 3 li nested inside of it

then we have figure with an img and figcaption nested inside of it

here we have another section
then a h2 as its subject with text cat Form

then we have a form element
with 2 fieledset
the first one include , two inputs of type radio, and labels respectivelly and one legend element

then we have a input with type text that has a place holder that a button with the type submit

then we have a footer element
with a p element with one a element wrapped arounf a word as an absolute path
