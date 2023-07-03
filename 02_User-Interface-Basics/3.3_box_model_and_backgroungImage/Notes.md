# Box model day 03



## backgrounf image

  - Background images in CSS allow you to set an image as the background of an element.
  - They are used to enhance the visual appeal, establish branding, set the tone, and create visual hierarchy on webpages.
  - in a nutshell it's for decoration and more elegent design .


- **synatx** 
```css
   .hero{
     background-image: url('image-url')
   }
   
   ```

   - `background-size`: images can be different sizes (small ,medium , large , very large)

   - based on sizes we use some properties to position the backgraound image as we want to 
   - `background-position : center or top ro bottom  ` or mixing them somehow to get what we want :)

- **problems may we face**

  - if the image is small then it will be reapeted to fill the whole width and content 
  - if its too big we have to position it based on what we want to see


  - for more experiment read leaner-gradient and radial-gradient
  - [more info here](https://cssgradient.io/)


  ## positions in css
  - **`positioning`** refers to the way elements are placed on a webpage. 
  - There are several positioning properties in `CSS`, but the most commonly used ones are `static`, `relative`, `absolute`, `fixed` ,`sticky`


  - **`Static Positioning`**:
By default, all HTML elements have the position: static property. Elements with static positioning follow the normal document flow and are positioned in the order they appear in the HTML. 
  - **`Relative Positioning`**:
Elements with position: relative are positioned relative to their normal position. They can be shifted using properties like `top`, `right`, `bottom`, and `left`. The surrounding elements are not affected by a relatively positioned element

  - **`Absolute Positioning`**:
An element with position: absolute is positioned relative to its nearest positioned ancestor (an ancestor with a positioning other than static). If there is no such ancestor, it will be positioned relative to the initial containing block, usually the browser window. Absolute positioning takes the element out of the normal document flow, so other elements don't consider its space

  - **`Fixed Positioning`**:
Elements with position: fixed are positioned relative to the browser window, regardless of scrolling. This means that even if the page is scrolled, a fixed element will remain at the same position on the screen  

  - **`sticky position`** is a positioning property in CSS that allows an element to remain in a specific position within its parent container or the viewport as the user scrolls. It combines aspects of both position: relative and position: fixed.

When an element is set to position: `sticky`, it behaves as position: relative until it reaches a specific scroll threshold defined by the developer. Once the element reaches that threshold, it becomes position: `fixed` and remains fixed in place.