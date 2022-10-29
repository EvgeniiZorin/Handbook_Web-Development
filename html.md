# Basics

`<img src="link/image.png" alt="alternative text">`

- `img` - element
- `src`, `alt` - attributes
- `<img>` - tag



# Tags

- `<main>` - opening tag
- `</main>` - closing tag

A tag for an element without a closing tab is called a self-closing tag:
- `<img>`

# Attributes

HTML attributes are special words used inside the opening tag of an element to control the element's behavior.

# Elements

`<element attribute1 attribute2></element>`

## Text

- `<h1>`
- `<p>` - paragraph; 
- `<main>` 
- `<section>`

## Emphasis `<em>`

## Strong `<strong>`




## Anchor `<a>`
`<a>` - "anchor"; links to other pages. 

`<a href="https://freecatphotoapp.com" target=_blank>text of the link</a>`

Attributes:
- `target=_blank` - open link in a new tab; 
- 

## Image `<img>`

Self-closing element. 

`<img src="link/image.png" alt="Alt text">`

attributes: alt - text that is displayed if the image fails to load. 

## Unordered list `<ul>`

```html
<ul>
  <li>cat nip</li>
  <li>laser pointers</li>
  <li>lasagna</li>
</ul>
```

## Ordered list `<ol>`

The code for an ordered list (ol) is similar to an unordered list, but list items in an ordered list are numbered when displayed.

## Figure `<figure>`

The figure element represents self-contained content and will allow you to associate an image with a caption.

A figure caption (figcaption) element is used to add a caption to describe the image contained within the figure element. For example, `<figcaption>A cute cat</figcaption>` adds the caption `A cute cat`.

## Form `<form>`

Attributes:
- `action` - indicates where form data should be sent


## Input `<input>`

Self-closing element. Inline element. 

Attributes:
- `type`: which type of input? e.g. `text`, `radio`
- `name`: In order for a form's data to be accessed by the location specified in the action attribute, you must give the text field a name attribute and assign it a value to represent the data being submitted.
- `placeholder`: Placeholder text is used to give people a hint about what kind of information to enter into an input.
- `required`: to prevent a user from submitting the form when the required info is missing
- `name`: if it's a button, we automatically deselect one button if the other is pressed. 

## Button `<button>`

Inline element. 

Attributes:
- `type`: to make it clear that it is a submit button; e.g. `submit`

## Label `<label>`

label elements are used to help associate the text for an input element with the input element itself (especially for assistive technologies like screen readers).

## Fieldset `<fieldset>`

The fieldset element is used to group related inputs and labels together in a web form. 
fieldset elements are block-level elements, meaning that they appear on a new line.

## Div

The div element is used mainly for design layout purposes unlike the other content elements you have used so far.


