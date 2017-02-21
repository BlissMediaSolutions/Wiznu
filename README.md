<p align="center">
<h1><b>Wiznu for Hair Website</b></h1>
<h4><b>A new Angular/Bootstrap website for: Wiznu for Hair (Hairdressing Salon)</b></h4>
<h5>Current website: www.wiznu.com.au </h5>

Status: Incomplete, Under Development

Developed with/for: HTML5, CSS3, Bootstrap v3, Angular, Javascript/JQuery, PHP 5.6

##### Tested in:
- Firefox 49.0.2
- Chrome 54.0.2
- Internet Explorer 11.0.9600

##### Notes:
- Website uses Google Maps API v3 - which requires a developer API Key (not included).
- HTML templates currently contain Javascript code, which should really be contained within the Angular Controllers.. (but hey, im just learning Angular, so its a dirty implementation/hack just to get the website functioning in a limited time frame).
- Website uses NanoGallery to display images from either Flickr or Google Photo's.
- Website Contact Form uses PHPMailer to relay an email thru GMail.  Due to SMTP headers being returned from PHP packaged with the data response for AJAX, JSON is converted to string in Angular & some simple string manipulation will remove the SMTP headers leaving us with the actual data response to display via Angular & DOM.

##### Developed by:
- Danielle Walker
