# Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


## Run Application
Simply open index.html with your web browser. On the bottom of the page the results from the tests will appear. 

# Tests

## 1. RSS Feeds:

### are defined
It tests to make sure that the allFeeds variable has been defined and that it is not empty.

### have URL defined
Loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty

### have name defined
Loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.

## 2. The Menu:

### is hidden by default
A test that ensures the menu element is hidden by default.

### changes visibility 
A test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.

## 3. Initial Entries:

### have at least a single element
A test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.

## 4. New Feed Selection:

### changes content
A test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.

