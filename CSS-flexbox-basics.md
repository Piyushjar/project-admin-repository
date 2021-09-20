# Basics

Alright, let's dive into the tutorial now. Flex is a display type that enables cards or any div to appear beside each other in a row. There are certain properties of flexbox that make it famous such as its responsiveness and more. Let's see how to use the basic flex display followed by other properties.

We first add the HTML code below:
```html
<div class="flex-box">
  <div>1</div>
  <div>2</div>
  <div>3</div>  
</div>
```

Then, we add the CSS code below:

```css
.flex-box {
  display: flex;
}
.flex-box > div {
  background:white;
  box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
  margin: 10px;
  border-radius:10px;
  padding: 20px;
  font-size: 30px;
}
```
The output would look like this:
image

If you observe the CSS code, you will understand that we only added a display of flex for our flexbox. Below it, we styled the boxes by giving them padding, color, and more. The main code necessary here is the display: flex; Next, we will look at the properties of flex to make it better.

Flex Direction The flex-direction property determines whether you would like the flex to arrange from left to right, right to left, top to bottom, or bottom to top. Below is the code for all these 4 directions. The row is horizontal and Column is vertical.
```css
flex-direction:row;
   flex-direction:row-reverse;
   flex-direction:column;
   flex-direction:column-reverse;
```
For example, I will be using the flex-direction: column in the photo below. The output would look like this:

image (1)

Flex Grow In this property, we can grow our flex boxes in a row to fill up the row completely if necessary. In other words, it defines how much space each flexbox should take up. For example, we can make one out of 3 flex-boxes to grow even more longer.







