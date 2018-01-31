behance-feed.js
============

Behance Feed is a simple way to add your behance last updates to your website.

## Installation
Setting up Behance-feed is pretty straight-forward. Just download the script and include it in your HTML:

```html
<script type="text/javascript" src="path/to/behance-feed.js"></script>
```

## Basic Usage

Add the apiKey and user variables to the global layout. Here's an example of getting a feed from Your_Username:

```html
<script>
  var apiKey = 'Your_Behance_API';
  var user = 'Your_Username';
</script>
```

Instafeed with automatically look for a `<div id="behance-feed"></div>` and fill it with linked thumbnails.

Also you can add the styles.css file or copy the content into your main css file in order to look good and start to make some changes to adapt it to your website style

```html
<link href="styles.css" rel="stylesheet">
```

If you have some questions you can rapidly go [here](https://codepen.io/ernestognw/pen/LQVPma) and check it.

## Requirements

You are gonna require __Bootstrap__ and __jQuery__ to get it work. Also, you've to get a valid __client id or API Key__ from Behance's developer website. You can easily register for one on [Behance's website](https://www.behance.net/dev/register).

If you need help with that step, just try Googling ["How to get an Behance API Key"](https://www.google.com.mx/search?q=how+to+get+a+behance+api+key&oq=how+to+get+a+behance+api+key&aqs=chrome..69i57j0.4817j0j7&sourceid=chrome&ie=UTF-8).

## Change Log

__1.0.0__

First realease. Everything just simple.
