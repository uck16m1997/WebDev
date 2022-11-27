# HTML

HTML is a markup language that defines all of the structures of the contents inside a document. We specify details of the content using set of standard elements that all browers will recognize.

- HTML5 is the latest standard for HTML 

## Tags
Tags are defined with angular brackets that wraps around a content <element *>text</* element>. Core HTML elements are defined as tags and some of them are also self closing.

## Boilerplate
- < !DOCTYPE html > is a flag used to signify we want to use latest features of html. 
- < html > element is used to contain the head and body elements of our document 
- < head > element is where we include style sheets,js modules and meta informaton such as title
- < body > element is used to contain all the contents of our document

## Entities
  - Start with & and end with ;
  - Used to display reserved characters
  https://html.spec.whatwg.org/multipage/named-characters.html


## Forms
Represents a document section containing interactive controls for submitting information.
- action attribute specifies WHERE the form data should be sent
- method attribute specifies which HTTP method should be used like GET, POST,...
- Contains input elements with varying types from text, password, checkbox, color, number, time, date, button ...
- label tag is used to match text label with the input tag by making for attribute of label same as inputs id
- button tag inside a form is used to submit the form unless told explicitly that it is a generic button by type="button" attribute
- name attribute for the input tag will be the name of the value of that tag when the form is sent to the action location


### References
  ---
  - https://html.spec.whatwg.org
  - https://developer.mozilla.org/en-US/ 
  - https://developer.mozilla.org/en-US/docs/Web/HTML/Element
  - https://docs.emmet.io
