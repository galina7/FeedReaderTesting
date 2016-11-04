# Project Overview

In this project is testin web-based application that reads Udacity RSS feeds. It includes and utilizes [Jasmine](http://jasmine.github.io/) testing frame. To be sure that tests are not running until the DOM is ready, all tests are placed within the $() function.

# Test Cases
1. Suite - RSS Feeds
  * Test to verify that all variable has been defined
  * Test to verify that all URLs are defined and not empty
  * Test to verify that all feeds have names defined and names are not empty

2. Suite - The Menu
  * Test to verify that menu is changing the visibility:
    *** visible when menu icon is clicked
    *** hidden when menu icon is clicked again

3. Suite - Initial Entries
  * Test to verify that loadFeed function is called and comletes its work, there is at least a sinle .entry element within the .feed container

4. Suite - New Feed Selection
  * Test to verify that when a new feed is loaded by the loadFeed function that the content actually changes

# How to run

Click on index.html or visit my GitHub page (https://github.com/galina7/FeedReaderTesting).

# Support

If you are having issues, please let us know.

# Contribute

Issue Tracker: https://github.com/galina7/FeedReaderTesting/issues
Source Code: https://github.com/galina7/FeedReaderTesting


