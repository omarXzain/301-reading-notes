# Javascript Templating
**Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source**

* The template is HTML markup with added templating tags that will either insert variables or run programming logic.


## Mustache 
- is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object.

- It is often referred to as “logic-less” because there are no if statements, else clauses, or for loops. Instead, there are only tags. mustache.js is an implementation of the mustache template system in JavaScript.



## Flexbox
The main idea behind the flex layout is to give the container the ability to alter its items’ width/height (and order) to best fill the available space (mostly to accommodate to all kind of display devices and screen sizes). A flex container expands items to fill available free space or shrinks them to prevent overflow.
<img src="https://i.ytimg.com/vi/wDGZEw3gXoE/maxresdefault.jpg" width=850 height=380>

- In flexbox layout, items are laid out following either the main axis or the cross axis:

1. main axis – The main axis of a flex container is the primary axis along which flex items are laid out.

2. main-start | main-end – The flex items are placed within the container starting from main-start and going to main-end.

3. main size – A flex item’s width or height, whichever is in the main dimension, is the item’s main size.

4. cross axis – The axis perpendicular to the main axis is called the cross axis. Its direction depends on the main axis direction.

5. cross-start | cross-end – Flex lines are filled with items and placed into the container starting on the cross-start side of the flex container and going toward the cross-end side.

6. cross size – The width or height of a flex item, whichever is in the cross dimension, is the item’s cross size.

## justify-content

<img src="https://user.oc-static.com/upload/2018/06/14/15289918266602_2.png" width=500 height=600>

- This defines the alignment along the main axis. It helps distribute extra free space leftover when either all the flex items on a line are inflexible, or are flexible but have reached their maximum size. It also exerts some control over the alignment of items when they overflow the line.

### Note
- there are also two additional keywords you can pair with these values: safe and unsafe. Using safe ensures that however you do this type of positioning, you can’t push an element such that it renders off-screen.

## flex
- This is the shorthand for flex-grow, flex-shrink and flex-basis combined. The second and third parameters

- Ex:
```
.item {
  flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ]
}
```

## Properties of flex items:
1. flex-grow.
2. flex-shrink.
3. flex-basis.
4. flex.
5. align-self.
6. align-items.
7. align-content.

### Note for you as a student
- It is recommended that you use this shorthand property rather than set the individual properties. The shorthand sets the other values intelligently.

__HAVE A NICE READ__

---------------------------------------------------------------------


[Table Of Content](https://omarxzain.github.io/301-reading-notes/read03)
