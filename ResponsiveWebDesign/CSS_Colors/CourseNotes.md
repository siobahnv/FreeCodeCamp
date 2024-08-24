# Responsive Web Design Certification: HTML and CSS
## Course: Learn CSS Colors by Building a Set of Colored Markers
Review/basic html structure building... <br>
_title_ element <br>
Can have multiple _meta_ elements <br>
_link_ element <br>
CSS rules (aka classes and selectors) <br>
_color keyword_ aka "red", "blue", "yellow" <br>
_shorthand property_ <br>
"When the shorthand _margin_ property has two values, it sets _margin-top_ and _margin-bottom_ to the first value, and _margin-left_ and _margin-right_ to the second value." <br>
Example: <br>
```
.class {
  margin: 10px auto;
}
```

"Multiple classes can be added to an element by listing them in the _class_ attribute and separating them with a space." <br>
Example: <br>
```
<div class="class1 class2 class3">
```
"If you add multiple classes to an HTML element, the styles of the first classes you list may be overridden by later classes." <br>

### Colors
Two main color models: "the _additive_ RGB (red, green, blue) model used in electronic devices, and the _subtractive_ CMYK (cyan, magenta, yellow, black) model used in print." <br>
RGB model: colors start off black and levels of red/green/blue are changed, from 0 to 255, 0 is 0%, 255 is 100% <br>
"In the additive RGB color model, primary colors are colors that, when combined, create pure white." <br>

"_Secondary_ colors are the colors you get when you combine primary colors." <br>
"_Tertiary_ colors are created by combining a primary with a nearby secondary color." <br>
"A color wheel is a circle where similar colors, or _hues_, are near each other, and different ones are further apart." <br>
"Two colors that are opposite from each other on the color wheel are called _complementary colors_." <br> 
"If two _complementary colors_ are combined, they produce gray." <br>
"It's better practice to choose one color as the dominant color, and use its complementary color as an accent to bring attention to certain content on the page." <br>

_hexadecimal_ or _hex values_: "Hex color values start with a # character and take six characters from 0-9 and A-F. The first pair of characters represent red, the second pair represent green, and the third pair represent blue. For example, #4B5320." <br>
"You may already be familiar with decimal, or base 10 values, which go from 0 - 9. Hexadecimal, or base 16 values, go from 0 - 9, then A - F, Example:" <br>
```
0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F
```
"With hex colors, 00 is 0% of that color, and FF is 100%." <br>

"The _HSL_ color model, or hue, saturation, and lightness, is another way to represent colors." <br>
"The CSS _hsl_ function accepts 3 values: a number from 0 to 360 for hue, a percentage from 0 to 100 for saturation, and a percentage from 0 to 100 for lightness." <br>
"If you imagine a color wheel, the hue red is at 0 degrees, green is at 120 degrees, and blue is at 240 degrees." <br>
"Saturation is the intensity of a color from 0%, or gray, to 100% for pure color. You must add the percent sign % to the saturation and lightness values." <br>
"Lightness is how bright a color appears, from 0%, or complete black, to 100%, complete white, with 50% being neutral." <br>

_Transition_ or _gradient_: "A gradient is when one color transitions into another. The CSS _linear-gradient_ function lets you control the direction of the transition along a line, and which colors are used." <br>
"One thing to remember is that the _linear-gradient_ function actually creates an _image_ element, and is usually paired with the _background_ property which can accept an image as a value." <br>
^^...what does this even mean? <br>
```
linear-gradient(gradientDirection, color1, color2, ...);
```

### Back to general styling and topics
function, values/arguments, actions <br>
