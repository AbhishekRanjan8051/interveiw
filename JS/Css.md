# CSS Interveiw Question

| N0. | Question                                                        |
| --- | --------------------------------------------------------------- |
| 1.  | [What is CSS position property?](#What-is-CSS-position-property) |

1. What is CSS position property?
   > The CSS position property defines the position of an element in a document. This property works with the left, right, top, bottom and z-index properties to determine the final position of an element on a page.

- There are five types of css position properties :-
  - static
  - relative
  - absolute
  - sticky
  - fixed

## Lets Discuss all the properties :-

- **STATIC**

  > - HTML Elememt are positioned **_static_** by default.
  > - Static element position are affected by top, bottom, left,right and z-index properties.
  > - An element with a static position always positioned according to the normal flow of the page.

  Example :-  
   **HTML**

  ```html
  <!DOCTYPE html>
  <html>
    <body>
      <h2>position: static;</h2>

      <p>
        An element with position: static; is not positioned in any special way;
        it is always positioned according to the normal flow of the page:
      </p>
      <div class="static">This div element has position: static;</div>
    </body>
  </html>
  ```

  **CSS**

  ```css
  .static {
    position: static;
    border: 3px solid #73ad21;
  }
  ```
