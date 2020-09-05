# Facebook Crawling Meta Data

Facebook link sharing meta tags. To optimize Web hosted content that people share to Facebook.

Facebook uses Facebook Crawler to crawl the meta tags of websites and make a shareable link on Facebook.

## Facebook Crawler Requirements

- Web server must use **gzip** and **deflate** encodings.
- Properties need to be **listed before the first 1 MB of your website** or it will be cutoff.
- Content need to be scraped by the crawler **within a few seconds** or unable to display the content.
- &nbsp;&nbsp;&nbsp;&nbsp; Facebook Developers Crawler Documentation https://developers.facebook.com/docs/sharing/webmasters/crawler

## Facebook Meta Tags

Use the HTML 5 meta tags to write the meta data.

&nbsp;&nbsp;&nbsp;&nbsp;```<meta property="og:title" content="Title of your web page."> </meta>```

Original Facebook Developers Documentation Link: https://developers.facebook.com/docs/sharing/webmasters/


## Basic Meta Tags

**og:url** undecorated URL without session variables.<br>

**og:title** Title of article/web page. <br>

**og:description** Short description of article/web page. 2 to 4 sentences. <br>

**fb:app_id** To use the Facebook insights and data generated from your Facebook Developers App. <br>
- Facebook Developers Dashboard &nbsp;&nbsp;&nbsp;&nbsp; https://developers.facebook.com/apps/redirect/dashboard <br>
- Facebook Insights Documnets &nbsp;&nbsp;&nbsp;&nbsp; https://developers.facebook.com/docs/sharing/referral-insights </br>

**og:type** Type of media for content. If not specified **website** will be used.<br>
- Media Types &nbsp;&nbsp;&nbsp;&nbsp; https://ogp.me/?fbclid=IwAR3B-fFZEqSNBnz4tyh2xPiz9WjngdO6Q63s_LZhV9HER_usJ9cEpovxMbA#types   <br>
 
**og:locale** For your localization default English is **en_US** <br>
- App Localization Facebook Developers Documnetation &nbsp;&nbsp;&nbsp;&nbsp; https://developers.facebook.com/docs/internationalization#locales <br>

**og:image** URL of image <br>
- Best practices of sharing image properties &nbsp;&nbsp;&nbsp;&nbsp; https://developers.facebook.com/docs/sharing/best-practices#images <br>
- Images are cached based on the URL and won't be updated unless the URL changes. <br>
- &nbsp;&nbsp;&nbsp;&nbsp; **og:image:secure_url** secure url https://  <br>
- &nbsp;&nbsp;&nbsp;&nbsp; **og:image:type** Image Type image/jpeg, image/gif image/png <br>
- &nbsp;&nbsp;&nbsp;&nbsp; **og:image:width** &nbsp; **og:image:height** Image width and Image height<br>


## Testing the markup
Enter the link you want to scrap into the following Facebook Debugger Tool.
> &nbsp;&nbsp;&nbsp;&nbsp; https://developers.facebook.com/tools/debug/


