# CSS Cheat Sheet

## Reference:
* https://www.w3schools.com/cssref/css_selectors.asp
* https://css-tricks.com/almanac/

Cascading Style Sheets at the most basic level it indicates that the order of CSS rules matter.


- **.class**: class selector
- **#id**: select element with matching id  
- &#42; : select all elements (usually on top)
- **element**: select specified html element
- **element1, element2**: select all element1 and element2
- **element1 element2**: select element1 and element2
- **element1 > element2**: select element2 elements where element1 is the parent element
- **element1 + element2**: select element2 that are placed directly after element1
- **:hover**: select on mouse hover
- **:last-child**: select element that is last of its parent
- **:first-child**: select elements that is first of its parents
- **!important**: rule with this property will always be applied regardless


### What seletors win out in the cascade depends on:

- Specificity
- Importance
- Source Order
