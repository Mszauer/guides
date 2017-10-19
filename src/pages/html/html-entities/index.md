---
title: HTML Entities
---
## HTML Entities
<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
HTML entities are an alternative, safe, way to write characters that are reserved. Using entities also allows you to write special characters that may not be present on your keyboard.
There are two ways to use entities: Name, and Number.

Entity Names begin with an `&` followed by a shortand name, such as "amp" for the ampersand (&). `&amp;`

Entity Numbers being with `&#` followed by the numeric value of the character, such as "38" for the ampersand (&). `&#38;`

### Why Use Entities
HTML Entities are very useful in situations where you want to display text that might be syntacticly similar to HTML elements. Take for example the Less Than sign, `<`. In HTML this less than is that starting block of an HTML element, which gets close with a Greater Than sign, `>`. This is where using the entity code comes in handy, and allows you to display these reserved characters as text on the display.
The different methods of using entities do have advantages and disadvantages:
<dl>
  <dd><strong>Advantage</strong> of using an entity name: An entity name is easy to remember.</dd>
  <dd><strong>Disadvantage</strong> of using an entity name: Browsers may not support all entity names, but the support for numbers is good.</dd>
</dl>

#### Examples
<dl>&#x000AE - &amp#x000AE</dl>
<dl>&#x000A9 - &amp#x000A9</dl>
<dl>&#x002DA - &amp#x002DA</dl>


#### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->
For a more complete list of HTML entities you can referance this table: https://dev.w3.org/html5/html-author/charref

