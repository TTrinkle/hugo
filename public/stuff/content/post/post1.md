+++
date = "2015-04-05T20:03:45-04:00"
title = "CSS Positioning"

+++

<p>
      The differences between relative, absolute and fixed positioning
    </p>
    <p>
        Understanding the differences between CSS position options can be confusing. If you find yourself randomly chosing a position and then checking what it does you probably do not have a good handle on the definitions of each 
    </p>
    <p>
        Relative: 
          In order to understand the relative positioning, we should first discuss what static does. Static is the default position of any element until you define a new one. Assigning all elements with a static position will stack them nicely on top of one another to the left. Positioning an element using relative will do exactly the same thing as static, until you apply a direction (top, right, bottom, left), at which point it will move the element accordingly. 

          Note: When applying a direction, the element requires a measurement (ex: left:100px;)
    </p>
    <p>
      Absolute: 
        Using Static and Relative positions require your element to still account for other elements on the page. They will move around each other while still be conscious of where things are. The absolute position does not act the same way. Think of it as putting blinders on your element, so it can only see and worry about it's location. When using an absolute position you must tell your element where to go using top, bottom, left, or right details. Once you've assigned an element to an absolute position, it will remain in that spot even when changing screen sizes. 
      </p>
      <p>
        Fixed:
          A fixed elements works similar to the absolute position. Also requiring details using top, bottom, right or left. However it will not move when you are scrolling on a page. It will remain fixed to the area you told it to be in. You may want to use a fixed position when creating a footer on your page so it stays at the bottom of the page regardless of where you are. 
      </p>
