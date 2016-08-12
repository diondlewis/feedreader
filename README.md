# Feedreader

This is a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! I have written additional tests to insure that the RSS feed functions as intended.
To run the application you can navigate in your browser to http://diondlewis.github.io/feedreader. You can also clone or download the repository to your computer.

## Feedreader Tests

The following tests should pass after successfully running the application.

**RSS Feeds:**
1. are defined
2. <br>
2. should have a url
3. <br>
3. should have a name

**The Menu:**
4. should be hidden by default
5. <br>
5. should change visibility when clicked.

**Initial Feeds:**
6. should have at least 1 entry in the feed container.

**New Feed Selection:**
7. should change content when loadFeed is called.
