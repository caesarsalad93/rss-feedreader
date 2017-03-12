# How to run the application
1. Clone this repo
2. Open the index.html file in a browser.
3. Scroll down to the bottom of the page, and the Jasmine test suite will be available for viewing.

# Project Overview

This is a web-based application that reads RSS feeds.   
I used the [Jasmine](https://jasmine.github.io/) testing framework to write unit tests for the application's core functionality.

## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

* Writing effective tests requires analyzing multiple aspects of an application including the HTML, CSS and JavaScript - an extremely important skill when changing teams or joining a new company.
* Good tests give you the ability to quickly analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.


# Testing Time

Write a test that...

* loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty. 
* loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty. 
* ensures the menu element is hidden by default
* ensures the menu changes visibility when the menu icon is clicked
* ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
* ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.

