html_css_tutorial
=================

CSS Cheat Sheet
---------------
start with a boilerplate and reset sheet. Good one here:

https://github.com/h5bp/html5-boilerplate/blob/master/css/style.css

import css file into another css file:

    @import url("base.css");

comments - surround the comment with /** and **/    Example:

    /** comments **/

common attributes:
------------------

div tags:

    width: 100px;  /** or 100% **/
    height: 100px;  /** or 100% **/
    border: 1px solid #ccc;  /** width, type, color **/
    border-bottom: 1px solid #ccc; /** applies border to one side - top,bottom,left,right **/

    /** margin and padding have the same format **/
    margin: 10px 9px 8px 7px;  /** top, right, bottom, left **/
    margin: 10px 20px 30px;  /** top, left/right, bottom **/
    margin: 10px 20px; /** top/bottom, left/right **/
    margin: 10px; /** top/right/bottom/left **/
    /** use these if you are only setting margin or border on one side **/
    margin-left: 10px;
    margin-right: 10px;
    margin-top: 10px;
    margin-bottom: 10px;

    /** auto will center an element left/right as long as there is a width specified on the div.  this may not work if float is used on div??? **/
    margin: 0 auto;

    /** ccc is shortcut for cccccc **/
    background-color: #ccc;
    background-color: #c123bb;

text:

    /** color specifies text color **/
    /** typically use 444 instead of 000 for dark text **/
    color: #444;

    font-size: 14px;

    /** you can specify multiple famlies.  The browser will use first one, but if it is not installed, it will go to the next family in the list **/
    font-family: 'Helvetica Neue', Arial, serif;
    font-weight: bold; /** bold or normal **/
    font-style: italic;
    text-decoration: underline;
    text-shadow: 1px 1px #444;




