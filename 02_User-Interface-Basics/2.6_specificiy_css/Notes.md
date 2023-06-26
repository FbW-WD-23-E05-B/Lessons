# User interface basics Day-06



## all people are equal !  

- provide equal access and equal opportunity to people with disabilities
- ***what is a screen reader ?***
- A blind individual uses a screen reader to navigate a website. The screen reader reads out the content, such as headings, links, and paragraphs, allowing the user to understand and interact with the information.
- [watch this video for better understandig of a screen reader](https://www.youtube.com/watch?v=dEbl5jvLKGQ&ab_channel=UCSFDocuments%26MediaPhotography)

- **most important ones => ( there are many of course ) :**
- using `semantic` tags as far as you can!
- `<title>` Tag used for title of the page
- `alt`  Attribute used for images 
- `aria-label` Attribute used for reading emojis or icons 


## Understanding the Cascade, Specificity, and Inheritance

###  Cascade
- The process by which styles are applied to HTML elements based on importance, specificity, and source order.

### Conflicting Rules
- css calculates and compares them like this **0,0,0,0** 


### Specificity

- A value assigned to CSS selectors that determines which styles take precedence. Inline styles have the highest specificity, followed by IDs, classes, attribute selectors, and elements.

**specificity based from high to low :**
1. inline styles
2. ids 
3. classes 
4. element tags => like (`h1`,`img`, `div` , `p` and so on ...  )

### Controlling Inheritance


- CSS provides keywords to control inheritance:
1. `initial` resets a property to its default value.
2. `unset`   default css that browser gives to every element 

3. `inherit` forces an element to inherit a specific property from its parent.