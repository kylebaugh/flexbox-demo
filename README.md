# Here’s a quick overview of the Flexbox mini-lecture this morning. 

## Flex is used to manipulate the arrangement and spacing of inner elements.

The four main CSS properties to use Flex are:
* Display
* Flex-Direction
* Justify-Content
* Align-Items

Let’s break those down.

## Display 

We use the display: flex; property in our CSS of a Parent element to allow us to manipulate the arrangement and spacing of its Child elements. 

## Flex-Direction

We use flex-direction to specify whether we want all of the Child elements arranged in either a row or a column. The default for flex-direction is row, but if you want your elements in a column, use flex-direction:column; in your Parent element CSS to apply that change.

### flex-direction: row
![flex direction row](https://github.com/kylebaugh/flexbox-demo/blob/main/flexRow.png)

## Justify-Content

We use justify-content to choose how we want our Child elements spaced within the Parent element. 

It is important to note that these changes will be applied along either the X-axis or Y-axis - depending on your Flex-Direction. If you are using flex-direction:row;, the changes will be along the X-axis (horizontally). If you’re using flex-direction:column;, the changes will be along the Y-axis (vertically).

There are a handful of values we can add to the justify-content property:

### justify-content: flex-start

Places all Child elements adjacent to each other, with no spaces, at the “beginning” of the Parent element - either top or left - depending on the flex-direction



### justify-content: flex-end

Places all Child elements adjacent to each other, with no spaces, at the “end” of the parent element - either bottom or right - depending on the flex-direction



### justify-content: center

Places all Child elements adjacent to each other, with no spaces, at the “center” of the Parent element - either horizontally or vertically - depending on the flex-direction




### justify-content: space-between

Spaces all Child elements with as much space between them as possible, pushing them all the way to the padding of the Parent element. 


### justify-content: space-evenly

Spaces all Child elements space between them AND the padding of the Parent element.



## Align-Items 

We use align-items to choose how we want our Child elements aligned within the Parent element on the axis OPPOSITE of our justify-content. That means when we’re using flex-direction:row;, our justify-content will be operating on the X-axis (horizontal), and our align-items would use the Y-axis (vertical). If we were using flex-direction:column;, the axes would be switched. 

With align-items, we only have three values that we usually use. Since we’ve already taken care of spacing, we just want to know to align them on our given axis.


### align-items: flex-start
Aligns Child elements at the “beginning” of the Parent element - either top or left - depending on the flex-direction. This is the default-setting for this parameter.




### align-items: flex-end

Aligns Child elements at the “end” of the Parent element - either bottom or right - depending on the flex-direction




### align-items: center

Centers Child elements along the given axis

# flexbox-demo
