# Overflow

it defines what happen when the children elements overflow their parent element size.

---

<br>

## Scroll :

---

We can choose the overflow of the elements to fit the parent element size as scroll :

```
overflow: scroll;
```

or we can choose one direction to scroll :

```
  overflow-x: auto (default) | hidden | scroll;
  overflow-y: auto (default) | hidden | scroll;
```

---

## scroll parts:

- **webkit-scroll properties** :

**webkit** : 

webkit is browser engine developed by Apple that supports number of special extensions in Css.



  by using the code below, we can adjust the scroll style

```
::-webkit-scrollbar              { /* 1 */ }
::-webkit-scrollbar-button       { /* 2 */ }
::-webkit-scrollbar-track        { /* 3 */ }
::-webkit-scrollbar-track-piece  { /* 4 */ }
::-webkit-scrollbar-thumb        { /* 5 */ }
::-webkit-scrollbar-corner       { /* 6 */ }
::-webkit-resizer                { /* 7 */ }
```

![Scroll parts](./assets/Screenshot%20from%202022-09-11%2014-17-21.png)

- **scroll-behavior**:

it controls how the scrollbar behaves when scrolling to a new position. instead of straight jumping to a new position (default behavior), it moves the scrollbar to the new position in animated way inside scrollable box.

```
  scroll-behavior: auto | smooth | unset (default);

```

- **Scroll-snap** :

it has two options: scroll-snap-type and scroll-snap-align

1- _scroll-snap-type_:

it's given for the parent element and takes 2 values, first value where to snap, second value how far the browser move content to align items.

- mandatory : snap to edge.

- proximity: browser take control when close to edge.

```
scroll-snap-type: x | y | both | inline | block | none (default) / mandatory | proximity
```

2- _scroll-snap-align:_

it's given for the children elements, which part of child you want to align.

```
scroll-snap-align: start | center | end | none (default)
```
