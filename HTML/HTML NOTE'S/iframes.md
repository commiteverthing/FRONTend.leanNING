---------> HTML <iframe> Tag

 <iframe src="https://www.w3schools.com" title="W3Schools Free Online Web Tutorials"></iframe> 

-------> Definition and Usage

The <iframe> tag specifies an inline frame.

An inline frame is used to embed another document within the current HTML document.

Tip: Use CSS to style the <iframe> (see example below). 

Tip: It is a good practice to always include a title attribute for the <iframe>. This is used by screen readers to read out what the content of the <iframe> is.



------> Attributes


Attribute 	Value 	Description
allow 	  	Specifies a feature policy for the <iframe>
allowfullscreen 	true
false 	Set to true if the <iframe> can activate fullscreen mode by calling the requestFullscreen() method
allowpaymentrequest 	true
false 	Set to true if a cross-origin <iframe> should be allowed to invoke the Payment Request API
height 	pixels 	Specifies the height of an <iframe>. Default height is 150 pixels
loading 	eager
lazy 	Specifies whether a browser should load an iframe immediately or to defer loading of iframes until some conditions are met
name 	text 	Specifies the name of an <iframe>
referrerpolicy 	no-referrer
no-referrer-when-downgrade
origin
origin-when-cross-origin
same-origin
strict-origin-when-cross-origin
unsafe-url 	Specifies which referrer information to send when fetching the iframe
sandbox 	allow-forms
allow-pointer-lock
allow-popups
allow-same-origin
allow-scripts
allow-top-navigation 	Enables an extra set of restrictions for the content in an <iframe>
src 	URL 	Specifies the address of the document to embed in the <iframe>
srcdoc 	HTML_code 	Specifies the HTML content of the page to show in the <iframe>
width 	pixels 	Specifies the width of an <iframe>. Default width is 300 pixels