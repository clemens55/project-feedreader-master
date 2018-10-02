# Project Overview
I wrote some tests for a feedreader template (Udacity) using Jasmine. 

### How to install
* Just download or clone the git project in a folder of your coice.
* Open the index.html in your web browser.

### What tests are included
* Test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
* Test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
* Test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
* Test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
* Test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
* Test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.

### Resources
* Google Fonts - https://fonts.google.com/
* Jasmine - https://jasmine.github.io/