Clean CSS
================
A node application that takes a link to a stylesheet as input, along with a CSV file specifying the webpages to crawl, and outputs a text file containing a list of all the unused CSS selectors from the stylesheet in that crawl.

How to set up the application
----
```
$ git clone https://github.com/diaryofdiscoveries/clean-css.git
$ cd clean-css
$ npm install
```
- Please add a stylesheet link to the index.js file (const stylesheet = {replace link here}).
- Please add a links.csv file to the project, specifying the webpages to crawl.

How to use the application
----
```
$ cd clean-css
$ node index.js
```
- Application outputs unused-selectors.txt file, listing all the unused CSS selectors from the crawl.

User Stories
----
```
As a user,
So that I can use this application for different websites,
I want to be able to choose any stylesheet to input to the application.

As a user,
So that I can be as broad or narrow in focus as I wish,
I want to be able to specify the webpages for the application to crawl.

As a user,
So that I can keep my page speeds as fast as possible,
I want to receive a list of all unused CSS selectors, so I can identify what Sass files I could safely delete.
```

Contributors
----
[Hubert Boma Manilla](https://github.com/bomsy) & [Zoë Hopkins](https://github.com/diaryofdiscoveries)
