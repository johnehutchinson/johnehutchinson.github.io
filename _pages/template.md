---
layout: template_with_toc
title: "Template"
permalink: /template/
author_profile: false 

---
This markdown file generates the html file _site/template/index.html

The layout file used is layouts/template_with_toc.html <br>
Note that template_with_toc.html calls default.html, which calls compress.html

The top menubar link to this file is in navigation.yml
  -  title: "Template"
  -  url: /template/

To automatically generate a table of contents, using the "Markdown All in One" extension, <br>
Place cursor where TOC should appear.<br>
In the command palette (cmd+shift+P) type and select Markdown All in One: Create Table of Contents

The sidebar has been manually created.  See the research page where the links are *clickable*.

The active menu item is brown and bold,<br>
 this was set in _sass/_navigation.scss
lines 54--58,<br>
/* Styles for the active menu item */
nav ul li.active a {<br>
  color: #8B4513; /* Change text color */<br>
  /* background-color: #007bff; */ /* Change background color */<br>
  /* font-weight: bold; */ /* Make the text bold */
