
# Feed Reader Testing

## Udacity Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.

## Project Test Suites

1. RSS Feeds
    * Test to confirm the allFeeds variable has been defined and that it is not empty.
    * Test to confirm each feed has a URL defined _and_ that the URL is not empty.
    * Test to confirm each feed has a name defined and that the name is not empty.
2. The Menu
    * Test to confirm the menu element is hidden by default.
    * Test to confirm the menu changes visibility when the menu icon is clicked.
3. Initial Entries
    * Test to confirm that when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
4. New Feed Selection
    * Test to confirm the content actually changes when a new feed is loaded by the `loadFeed` function.

## Running The Tests

To run the tests, open the index.html file in a browser.

## Dependencies

Jasmine 3.3.0
JQuery 3.3.1
Handlebars 4.0.12
Google JavaScript API Loader
Google Fonts

## Notes

This project utilized starter project code provided by Udacity at [https://github.com/udacity/fend-project-memory-game](https://github.com/udacity/fend-project-memory-game).  The starter project code consisted of HTML and CSS styling to display a static version of the Memory Game project along with a javascript shuffle function.
