## ITMD 361, Production Problem 3: Relative Units in CSS

For this production problem, you will be doing some math using the formula we talked about in class
on September 21. Specifically,

    target ÷ context = result

Remember that, by default, most browsers set 1em = 16px.

You’ll then use that to compute the values for the CSS styles below.

1. Convert the base font-size listed here from pixels to ems:

      html {
        font-size: 1.1875em; /* 19px / 16px */
      }

2.  Convert the base font-size listed here to ems, and set the line-height in ems accordingly:

      html {
        font-size: 1.0625em; /* 17px / 16px */
        line-height: 1.4117em; /* 24px / 17px */
      }

3. Set the padding for this page to 12px on top and bottom, and 6px on left and right. Express in
ems:

      html {
        font-size: 1.125em; /* 18px / 16px */
        padding: 0.75em 0.375em 0.75em 0.375em; /* 12px / 16px, 6px / 16px */ 
      }

4. Consider the following CSS. Assuming a browser with its base size at 1em = 16px, how big is h2,
in pixels?

      html {
        font-size: 1.125em;
      }
      figure {
        font-size: 0.888em;
      }
      figure h2 {
        font-size: 1.4375em; /* h2 is 23px; 23px / 16px = 1.43723em */
      }
