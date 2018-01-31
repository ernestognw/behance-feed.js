behance-feed.js
============

Behance Feed is a simple way to add your behance last updates to your website.

## Installation
Setting up Behance-feed is pretty straight-forward. Just download the script and include it in your HTML:

```html
<script type="text/javascript" src="path/to/behance-feed.js"></script>
```

## Basic Usage

Add the apiKey and user variables to the global layout. Here's an example of getting a feed from __/ramotion__:

```html
<script>
  var apiKey = 'ycN420C1IQyzg3vaclQ5uXOMhx0toixh'; // Your API Key/Client ID. 
  // If you don't have one, go get it here: https://www.behance.net/dev/register
  var user = 'ramotion'; // This is your behance username
</script
```

Instafeed with automatically look for a `<div id="behance-feed"></div>` and fill it with linked thumbnails.

## Requirements

The only thing you'll need to get going is a valid __client id or API Key__ from Behance's developer website. You can easily register for one on [Behance's website](https://www.behance.net/dev/register).

If you need help with that step, just try Googling ["How to get an Behance API Key"](https://www.google.com.mx/search?q=how+to+get+a+behance+api+key&oq=how+to+get+a+behance+api+key&aqs=chrome..69i57j0.4817j0j7&sourceid=chrome&ie=UTF-8).

## Change Log

__1.0.0__

First realease. Everything just simple.
