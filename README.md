# Feed Reader Testing Project Overview

The Feed Reader is a web-based application that reads RSS feeds. Jasmine was used to write a number of tests against this pre- existing application. This will test the underlying business logic of the application as well as the event handling and DOM manipulation.


## Test that was carried out on the application

### RSS Feed

* To ensure that the allFeeds variable has been defined and that it is not empty.
* To ensure that the allFeeds object have a url defined and that url is not empty. 
* To ensure that the allFeeds object have a name defined and that name is not empty. 

### The Menu

* A test that ensures the menu element is hidden by default. 
* A test that display the menu when the menu icon is clicked and hide the menu when the menu icon is clicked again.

### Initial Entries

* To test if the loadfeed function has at least one entry

### New Feed Selection

* Feed content changes when new feed is selected.

## Instruction to run the application successfully

* download the zipped file of this project by clicking on 'download zip' when
  you click on the 'download or clone' button under the repo name.
* or clone this repo.
* cd into the directory you want the cloned directory to be.
* locate the index.html file in the project directory.
* run the applicaton by opening the index file in a browser.