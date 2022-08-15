Website: https://gettingstartedwith.css.education/

--- 

# Learning notes 

## Tools

- color palette explorer : https://color.adobe.com/fr/explore
- font pairer : https://www.fontpair.co/all

## Tips

- box sizing trick (border box model) : https://css-tricks.com/box-sizing/
- the `*` selector has almost no specificity and is weaker than the an html element selector.
- Line height must be proportional, that's why the unit is left out.
- when resetting a `nav>ul` set `padding` and `margin` to `0` because you don't know which style the client browser is applying by default. 

The 20/80 rule of FlexBox layout and nav bars: learn what this properties do:
```css
  display: flex;
  flex-flow: row wrap;
  justify-content: center;
  align-items: center;
  gap: 2rem;
```
