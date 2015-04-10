# Web Page containing Image Slider and Wiki Search Box

This web page is built using **HTML5** . The styling of this page has been done using **CSS3 Scripts (Bootstrap)**. The page contains an Image Slider as the background filling most of the page , the Image Slider has been built using **jQuery Scripts**.

The page contains a *Google Custom Search Box* ,the Search Box uses **AJAX** to retrieve server side information from https://en.wikipedia.org/ , thereby creating a *Wikipedia Search Box*. The **AJAX** code used for the Search Box is :

(function() {
var cx = '009319930026121832260:75itm7znvtm';
var gcse = document.createElement('script');
gcse.type = 'text/javascript';
gcse.async = true;
gcse.src = (document.location.protocol == 'https:' ? 'https:' : 'http:') +
'//www.google.com/cse/cse.js?cx=' + cx;
var s = document.getElementsByTagName('script')[0];
s.parentNode.insertBefore(gcse, s);
})();
