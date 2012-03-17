# Feed-discover

[![Build Status](https://secure.travis-ci.org/sentientwaffle/google-feeds.png?branch=master)](http://travis-ci.org/sentientwaffle/google-feeds)

Search for feeds using the
[Google Feeds JSON API](https://developers.google.com/feed/v1/jsondevguide).

# Installation

    $ npm install google-feeds

# Usage

Each feed url is an Object with properties "source", "link", and "title".

    var gfeeds = require('google-feeds');

    gfeeds("Node.js blogs", function(err, feed_urls) {
      
    });


# License
See LICENSE.
