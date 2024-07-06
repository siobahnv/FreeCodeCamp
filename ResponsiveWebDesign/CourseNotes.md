# Responsive Web Design Certification: HTML and CSS

## Tags
Elements <br>
Opening and Closing <br>
H1 through H6 <br>
```
<p>Paragraph</p>
<!-- Comment Note Tag -->
<main>Main Content</main>
```

### Nesting (indentation 2 spaces)
img tag has opening, but no closing tag <br>
_void element:_ opening, but no closing tag <br>

## HTML Attributes
Example _src_ inside _img_ tag <br>
_alt_ attribute <br>
```
<img src="URL">
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
_input_ element is a _void_ element to collect data/input from a form<br>
_type_ attribute can be used to definte _input_ elements <br>
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