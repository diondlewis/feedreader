# Feedreader

This is a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! I have written additional tests to insure that the RSS feed functions as intended. To run the application, clone or download the repository at https://github.com/diondlewis/feedreader to your computer and open the index.html file in your browser.

## Feedreader Tests

The following tests should pass after successfully running the application.

### RSS Feeds:
are defined
<br>
should have a url
<br>
should have a name

### The Menu:
should be hidden by default
<br>
should change visibility when clicked

### Initial Feeds:
should have at least 1 entry in the feed container

###New Feed Selection:
should change content when loadFeed is called
