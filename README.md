# Feedreader

This is a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! I have written additional tests to insure that the RSS feed functions as intended.
To run the application you can navigate in your browser to http://diondlewis.github.io/feedreader. You can also clone or download the repository to your computer.

## Feedreader Tests

The following tests should pass after successfully running the application.

### RSS Feeds:
are defined
should have a url
should have a name

### The Menu:**
should be hidden by default
should change visibility when clicked.

### Initial Feeds:
should have at least 1 entry in the feed container.

**New Feed Selection:**
should change content when loadFeed is called.
