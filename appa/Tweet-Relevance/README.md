# Overview

This GAE project provides sample code that demonstrates how to create a minimal web app
that logins users with their Twitter account and displays only their most relevant tweets
(as determined by a trivial algorithm that can easily be modified/extended) as part of a 
UX that is optimized for a mobile client. First-time visitors get to login free for a number
of times and experience the app before they are requested to purchase additional logins to
continue using the app.

# Credits

Mike Knapp's https://github.com/mikeknapp/AppEngine-OAuth-Library project is used to 
handle making OAuth requests to Twitter.

The application's primary UI is adapted from the final installment of SitePen's TweetView
project at http://dojotoolkit.org/documentation/tutorials/1.6/mobile/tweetview/packaging/ 
and is intended to be delivered to a mobile display like an iPhone, although development
works fine on a desktop browser like WebKit. The UI for the payflows is minimal.

# Getting Started

Follow these steps to get up and running:

* Download this project's source code
* Configure the source code as a Google App Engine project
* Create a Twitter account 
* Create a sample Twitter application
* Copy twitter_config.template.py to twitter_config.py and fill in the Twitter OAuth credentials
* Launch the project, and optionally access it through a mobile browser (or mobile browser simulator.)

# Screenshot

![screenshot!](https://github.com/ptwobrussell/Tweet-Relevance/raw/master/screenshot.png)

Provided by: Zaffra, LLC - http://zaffra.com
