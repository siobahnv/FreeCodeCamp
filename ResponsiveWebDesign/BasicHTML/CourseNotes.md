# Responsive Web Design Certification: HTML and CSS

## Tags
Elements <br>
Opening and Closing <br>
H1 through H6 <br>
```
<h1>TEXT</h1>
<p>Paragraph</p>
<!-- Comment Note Tag -->
<main>Main Content</main>
```

### Nesting (indentation 2 spaces)
_img_ tag has opening, but no closing tag <br>
_void element:_ is a tag with an opening, but no closing tag <br>

## HTML Attributes
Example _src_ inside _img_ tag <br>
_alt_ attribute provides useful alternative text<br>
```
<img src="URL" alt="TEXT">
```
Anchor "a" element <br>
Text needs to be between the anchor elements; any text, image, or element can be turned into a link.
```
<a img src="URL">Text for link here</a>
```
_target_ attribute specifics where/how to open links <br>
_target="_blank"_ opens to a new window or tab <br>
```
<a href="URL" target="_blank">TEXT</a>
```

## Section Element
A section element can define chapters, headers, footers, or any other sections of content.
```
<section>
  <h2>Section Title</h2>
  <p>Section content...</p>
</section>
```

## Lists
_ul_ unordered list <br>
_ol_ ordered (numbered) list <br>
_li_ list item <br>

## More Elements
_figure_ element "represents self-contained content and will allow you to associate an image with a caption" <br>
(not really heard of this one before?) <br>
_figure caption_ element "figcaption" is to add a caption for the image in a _figure_ element <br>
```
<figure>
  <img src="URL" alt="TEXT>
  <figcaption>TEXT</figcaption>
</figure>
```

_em_ element to add emphasize (italicize) <br>
_strong_ element to add importance or strength (bold) <br>

_form_ element to create a form to collect input <br>
_action_ attribute is where the form data is to be sent <br>
_input_ element is a _void_ element to collect data/input from a form; does not have a closing tag, value needs a leading space <br>
_type_ attribute can be used to definte _input_ elements <br>
_type_ attributes for different _inputs_ can include: text, radio (button), checkbox, etc. <br>
_name_ attribute represents the data being submitted and can be assigned a value <br>
_placeholder text_ can be used to give hints <br>
_required_ attribute can be used to require certain input, does not require a set value, needs space around <br>
_button_ element is used to create a clickable button <br>

```
<form action="SUBMIT_URL">
  <input required type="text" name="VALUE" placeholder="hint hint">
  <button type="VALUE">TEXT_EXAMPLE_SUBMIT</button>
</form>
```

_inline_ elements don't appear on new lines <br>

_radio_ buttons can be used when you want one of multiple answers <br>
_label_ elements "are used to help associate the text for an input element with the input element itself (especially for assistive technologies like screen readers)." <br>
_id_ attribute is used to identify specific _unique_ HTML elements <br>
"When elements have multiple attributes, the order of the attributes doesn't matter." <br>
_Groups_ of radio buttons must all have a _name_ attribute with the same _value_. <br>
_value_ attribute distinguishes values between buttons/inputs. <br>

```
<form action="SUBMIT_URL">
  <label><input id="unique1" type="radio" name="Group1" value="option1"> Option 1</label>
  <label><input id="unique2" type="radio" name="Group1" value="option2"> Option 2</label>
  <button type="VALUE">TEXT_EXAMPLE_SUBMIT</button>
</form>
```

_fieldset_ element groups related inputs and labels in a form <br>
_block-level elements_ appear on a new line <br>
_fieldset_ elements are _block-level elements_ <br>
_legend_ element acts as a caption for the _fieldset_ element (Q for A) <br>

```
<form action="SUBMIT_URL">
  <fieldset>
    <legend>QUESTION</legend>
    <label><input id="unique1" type="radio" name="Group1" value="option1"> Option 1</label>
    <label><input id="unique2" type="radio" name="Group1" value="option2"> Option 2</label>
  </fieldset>
</form>
```

Use _type_ "checkbox" for inputs with multiple answers <br>
Can use _for_ attribute with _label_ element and _id_ attribute to nest/associate an _input_ element's text <br>
_name / value_ attribute pairs; _value_ is optional <br>
_checked_ attribute can default a radio button or checkbox to selected/checkmarked; similar to _required_ attribute, needs spaces around, no value <br>

```
<form action="SUBMIT_URL">
  <fieldset>
    <legend>QUESTION</legend>
    <label><input checked id="unique1" type="checkbox" name="Group1" value="option1"> Option 1</label>
    <label><input id="unique2" type="checkbox" name="Group1" value="option2"> Option 2</label>

    <input id="UNIQUE_VALUE" type="value" name="VALUE" value="UNIQUE_VALUE"> <label for="UNIQUE_VALUE"> TEXT </label>
  </fieldset>
</form>
```

_footer_ element typically contains info about author, terms, copyright, contact, etc. <br>
all page content goes inside the _body_ element <br>
other important information goes inside the _head_ element such as _metadata_ <br>
_title_ element determines what browsers show in the title bar or tab for the page and goes inside the _head_ element <br>
entire contents of a page are nested inside an _html_ element <br>
_html_ element is the root of an HTML page and wraps all content <br>
can specify the language of a page by adding _lang_ attribute to _html_ element <br>
all pages should begin with _<!DOCTYPE html>_; this "special string is known as a declaration and ensures the browser tries to meet industry-wide specifications" <br>
can define browser behavior by setting _meta_ elements inside the _head_ element <br>
_meta_ elements are _void_ elements <br>

```
<meta attribute="value">
```

