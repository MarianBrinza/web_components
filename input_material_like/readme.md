### Contains an input component - HTML & CSS only

**How does it work ?**

- we have an outer div surounding the elements, this has 100% width & height
- the outer div contains:

|> div
|   > input
|   > label
|       > span

- we make the `input`, the `label` and `label:after` fill the parent
- `label` and `label:after` are positioned absolute

- the animation is from `border-bottom` on  `label:after`
- we take advantage of html attributes: `focus` and `required` and we use css selectors `:focus & :valid`
- when the input receives `focus` we `translateX` the `label:after` border 100%
- if the input is `valid` we `translateX` the `label:after` border 0%
