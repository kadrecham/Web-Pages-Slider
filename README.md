# Web-Pages-Slider
## Javascript solution to present many web pages as slideshow

We modified the [origin engine](https://www.daniweb.com/programming/web-development/code/216730/siteshow-create-a-slideshow-of-web-pages) to allow the users to add, remove and change position of the web pages directly from the menu, in addition to enter the name and the appearance time for each slide, besides to store the URLs for the added webpages to reopen them again directlly  when you restart the slider .  
  
Host the HTML file in web server like [Apache Web Server](https://httpd.apache.org/) to get all of properties of this slider like the movement effects and storing the URLs.  
  
![alt tag](https://user-images.githubusercontent.com/25906706/28717121-c7cf3658-73a0-11e7-9794-07b2e204aa69.png)

### Note:
Because this solution depends on iframe tags and some web pages deny X-Frame option, so browser shouldn't be allowed to render those pages in iframe. More information [HERE](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)
