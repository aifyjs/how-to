# A Short Guide to AIFY.JS

## What is aify.js?
 
In the simplest terms, aify.js is a library which when embedded on your web page, can quickly add the power of AI to your website in the form of several features, without you having to invest in any backend or machine learning costs.

## How to use aify.js?

1. Log on to [Aify Dashboard](https://568bd7cf.ngrok.io/) and Login or Create Account.
1.5 After account creation, Login to your account. 
2. On the left menu, Click on Websites > Add
3. Add your website, enter any name for your website and enter the root URL of the site.
4. Ensure that your website has a publicly accessible sitemap file, preferably at [/sitemap.xml](https://example.com/sitemap.xml) location. Our Aify Crawler will use this sitemap to crawl your website.
5. Wait for 10-15 mins for the Aify Crawler to visit your website and work its magic in the background.
6. On your web page, include the following line to import the AifyJS package into your application - 
```
<script src="https://raw.githubusercontent.com/xprilion/aifyjs/master/docs/aify.js"></script>
```
7. In your web page, use the following line to instantiate a connection to the Aify API - 
```
var ai = new aifyjs();
```
8. To generate element labels on the web page, use the following line - 
```
ai.labels();
```
9. To fetch captions for the images on the page, use the following line - 
```
ai.captions();
```
10. When your page loads, it will silently cause an update of the page source to reflect the labels and captions fetched from the Aify API.
11. Voila! Your website is more accessible to people with visual challenges now! :slight_smile:

## Already deployed usage sample

You can check out - [aifyjs.github.io](https://aifyjs.github.io) for an already deployed sample of the library in action! 

## Errors? Problems?

Shoot as an email at - thecodefoundation@gmail.com

## Team - 

- Anubhav (xprilion@gmail.com)
- Ritwik (ritwikraha.nsec@gmail.com)
- Ankit (ankitnsec98@gmail.com)
- Ayush (mein2work@gmail.com)
- Debroop (debroop42@gmail.com)
