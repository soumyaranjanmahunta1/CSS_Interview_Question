# CSS_Interview_Question

Q1-how to add comments on css?
Ans:- /*   */

Q2-Why do we use pseudo-class?   
Ans:-A pseudo-class is used to define a special state of an element. For example, it can be used to: Style an element when a user mouses over it. Style visited and unvisited links differently.
Ex:-a:hover {                
  color: hotpink;
}

Q3:-How is specificity applied?
Ans:-Specificity is an algorithm that calculates the weight that is applied to a given CSS declaration. The weight is determined by the number of selectors of each weight category in the selector matching the element (or pseudo-element)

Q4:-What method allows an element to be moved from its current position?
Ans:-The translate() method moves an element from its current position (according to the parameters given for the X-axis and the Y-axis).
Ex:-div {
  transform: translate(50px, 100px);  //50px-x axis 100px-y axis
}

Q5:-what properties does flex model have?
Ans:-
      order.
      flex-grow.
      flex-shrink.
      flex-basis.
      flex.
      align-self.

Q6:-What is the difference between flex and grids?
Ans:-The basic difference between CSS Grid Layout and CSS Flexbox Layout is that flexbox was designed for layout in one dimension - either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time.

Q7:-Give an example where we have to use grids and where you have to use flexbox?
Ans:-
       1:-Flexbox is ideal when you have a small layout design to implement, with a few rows or a few columns
       2:-In some use cases, we have complex designs to implement, and that’s when the magic of CSS Grid shows itself. The two-dimensional layout system here is perfect to create a complex design. We can use it in our favor to create more complex and maintainable web pages
       3:- if we want somthing in single direction in that case we have use flex but in case we want somthing in two-dimensional thrn we can go for display grid.

Q8:-Give an example where you cannot use flexbox, and you can only use grids?
Ans:-Of course, you can build your whole application using only Flexbox and get the same result as if you were building with CSS grid. But for a better CSS approach, to have a more concise, well-written, and maintainable application in the long-term, to create and fit your layout perfectly, the ideal method is to use CSS Grid.

Q9:-What are combinators? give examples of how you can use them
Ans:-A combinator is something that explains the relationship between the selectors. A CSS selector can contain more than one simple selector.
      descendant selector (space)
      child selector (>)
      adjacent sibling selector (+)
      general sibling selector (~)

Q10:-What does object-fit do?
Ans:-The CSS object-fit property is used to specify how an <img> or <video> should be resized to fit its container.
Ex:-//object-fit: cover,//object-fit: fill,//object-fit: contain.//object-fit: none;

Q11:-What does rotate do?
Ans:-Change rotation of an element;
Ex:-    div {
              rotate: 30deg;
            }
