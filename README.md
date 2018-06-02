Clean CSS
================
A simple node application that takes a link to a stylesheet as input (currently hardcoded), and outputs a text file containing a list of all the unused CSS selectors remaining after crawling through the specified webpages (provided links).

How to set up the application
----
```
$ git clone https://github.com/diaryofdiscoveries/clean-css.git
$ cd clean-css
$ npm install
$ node index.js
```
- Please add a links.csv file to the project, specifying the webpages to crawl.

How to use the application
----
```
$ cd clean-css
$ node index.js
```
- Application outputs unused-selectors.txt file.

User Stories
----
```
As a user,
So that I can use this application for different websites,
I want to be able to choose any stylesheet link to input to the application.

As a user,
So that I can be as broad or narrow in focus as I wish,
I want to be able to specify the list of links for the application to crawl.

As a user,
So that I can keep my page speeds as fast as possible,
I want to receive a list of all unused CSS selectors, so I can identify what Sass files I could safely delete.
```
