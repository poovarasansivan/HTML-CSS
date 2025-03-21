# Task Name - Create a Card Component with Hover Effect

# Objective

- Create a Card component with a image, title, description and some basic CSS styling and transitions.

# Elements Used

1. Html Elements

- `<div>` - To group elements.
- `<img>` - To add images inside the webpage.
- `Class Name` - To provide a alias name for an html element and use this classname to apply a CSS.
- `<p>` - It defines a parah of content.
- `<h>` - It defines a heading of the page.

2. CSS Elements

- `font-size` - To set a font size.
- `font-weight` - To set a font weight either bold or medium.
- `color` - To define the text color.
- `text-algin` - To define the text algin (eg. center,start,end).
- `background-color` - To define the background color of page or a section.
- `flex` and `flex-direction` - To define the page elements according to flex rules and aligns the content according to flex-direction.
- `margin` - To add a space around the elements.
- `width` and `height` - To define the width and height of the html elements.
- `@media screen and (max-width: 600px)` - Using media query to define the css for different screen size.

# Task Performed

- Created a card with image, title, description along with transition and over affect.
- Added this Card with TASk 1 simple web page layout and made it better.
- Below is my card component code (Both html and css).

```
<div class="container">
    <div class="Card-image">
        <img src="csk.png" alt="csk banner"/>
    </div>
    <div class="card-title">
        <p>Chennai Super Kings Squad</p>
    </div>
    <div class="description">
        <p>CSK Squad 2025 is packed with experienced stars and fresh talents, ready to chase another IPL title!
        </p>
   </div>
</div>
```
.container {
  background: white;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  padding: 1rem;
  max-width: 300px;
  margin: auto;
  transition: transform 0.3s, background-color 0.3s;
}
.container:hover {
  transform: translateX(-5px);
  background-color: rgb(248, 248, 29);
}

.Card-image {
  text-align: center;
}

.Card-image img {
  max-width: 300px;
  object-fit: contain;
}

.card-title {
  font-size: 1.2rem;
  font-weight: bold;
  margin: 0.5rem 0;
  text-align: center;
}

.description {
  font-size: 1rem;
  margin: 0.5rem 0;
  text-align: justify;
}

```
