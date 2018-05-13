# GoTop
A simple animated scroll "Go to Top" javascript with no dependencies within only 862 Bytes (517 Bytes gziped) to do the trick.

## Demo & How to use

Just add the script before your last `</body>` tag and a link with an ID "gotop" into your page:

    <a href="#top" title=" Go to Top " id="gotop">↑ <span>Top</span></a>

That's all!
You can specify an anchor as a target for fallback (if javascript is disabled).

## Settings

The [first strings into the script](https://github.com/cara-tm/GoTop/blob/master/GoTop.min.js#L2) allow you to set some variables which govern the behaviours:

* `showme`: Set to `1` to show the link on page load or set to `0` to hidde it on page load
* `distance`: The distance in pixels from the bottom of the HTML document when the go top link appears. Default: `300`
* `fromTop`: Set to `1` for the link's revelation based on the `distance` value from the top of the document, set to `0` for opposite.
* `link`: The ID name associated to your link. Default: `'gotop'`
* `adjust`: Allows to correct the final position in pixels to the top of the HTML document on the scrolling animation (if needed: due to extra spaces (personal bookmarks, extensions, etc.) into the browsers window. Despite the script evaluate this behavior, consider this as a fallback for old browsers). Default: `100`

See [the `demo.html` file for example](https://github.com/cara-tm/GoTop/blob/master/demo.html "Discover").

See it in action here: [https://jsfiddle.net/f987rqgw/](https://jsfiddle.net/f987rqgw/5/ "Try it")

## Browsers Support

Despite the anchor target as a fallback, tested successfuly within:

* Google Chromium 1 and up;
* FireFox 1.0.8 and up;
* Safari;
* Opera 0.8 and up;
* Midori 0.4 and up;
* Netscape Navigator 7.1;
* Internet Explorer all versions.
