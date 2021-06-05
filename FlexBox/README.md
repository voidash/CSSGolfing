# FlexBox

- **main axis** : primary axis along which items are laid out. depnends on `flex-direction` 
- **main start** : flex items are placed within container starting from main-start and going to main-end
- **main-size** : A flex item width or height, whichever is the main dimension, is item main size. 
- other ones are **cross axis**, **cross start** and **cross size** , they are opposite of what `flex direction` defines

# options

- `flex-direction` : defines the main axis, if row is selected then main axis will be horizontal. 
- `flex-wrap` : defines whether the items inside the flex container should fit in a line , or can they move down. options : `nowrap | wrap | wrap reverse`
- `align-items`: how items will position themself in container with respect to cross axis. 
- `justify-content` : how content should be justified. similar to `mainAxisAlignment` in flutter
- `align-content` : `justify-content` for cross axis but for whole child collection. `crossAxisAlignment` in flutter. this only takes effect if flex-wrap is set to `wrap`
- `align-items` : for each items

## option for single item(Children) inside flexbox container

-  `align-self` : auto | flex-start | flex-end | center | baseline | stretch;
- `order` : default is 0
- `flex-grow` : how much should it grow with respect to other. `flexible` in flutter
- `flex-shrink`: similar to flex-grow but shrinking behaviour
- `flex-basis`


