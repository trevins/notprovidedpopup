not provided popup
================

An annoying popup to gather keyword data from Google. Based off of this: http://hallofhavoc.com/2013/05/how-to-create-an-overlay-popup-box-using-html-css-and-jquery/


Greetings! Get ready to get your keyword data back like it's 2008. 

Based off of: http://hallofhavoc.com/2013/05/how-to-create-an-overlay-popup-box-using-html-css-and-jquery/

\\\\\\\\\\\\\\INSTRUCTIONS\\\\\\\\\\\\\\

1. Upload custom.js and overlaypop.css to your root.

2. Add these lines to the <head> of whatever pages you want the popup to display on

<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.0/jquery.min.js"></script>
<script type="text/javascript" src="custom.js"></script>
<link href='overlaypopup.css' rel='stylesheet' type='text/css'>

3. Add this HTML in the body of the page you want the code to display on:

<div>
<div>
<h2>Quick favor to ask</h2>
<p>If you came to my site from a search engine, please enter the keyword that you searched with below:</p>
<input type="text" maxlength="255" value=""/>
<button>Close</button>
</div>
</div>

4. You can ingreate the form to email you with all of the data. You are on your own for that though :D

5. Profit?
