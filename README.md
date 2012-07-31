Description
=======================

Repo to store the html/files for use in the displaying of subject area links in the site menu block.

Usage
=======================

The folder hierarchy should be as follows

`<subject area (with spaces removed)>/index.htm`

Then other files can also be added under the subject area folder. In the HTML file, don't include an `<html>` or `<body>` tag, since it will be included in a Moodle page. In the HTML file you can use variable %www_root% to properly link to your files.

For example, 

NURSING/index.htm
NURSING/document.pdf

In NURSING/index.htm you can link to "NURSING/document.pdf" by creating the following link tag:

`<a href="%www_root%/NURSING/document.pdf">document.pdf</a>`

The %www_root% variable will be replaced by the proper path to where it is located in Moodle.