# Armando Pérez
## Description
In this project you'll learn to add filtering to a portfolio page using .addClass and .removeClass.

## Objective
Armando Pérez wants to add filtering to his portfolio page. [Here's what it looks like]("https://s3.amazonaws.com/codecademy-content/projects/2/armando-perez/index.html"). When a nav pill is clicked, different images on the page are selected.

## Tasks
### 1.
Look at __index.html__:

In `<div class="main">`, there are three rows, each containing three columns. In each column, there is a `<a class="thumbnail">` element. There are four categories of thumbnail elements: `<a class="consumer thumbnail">`, <`a class="mobile thumbnail">`, `<a class="commerce thumbnail">`, `<a class="enterprise thumbnail">`.

In the `<ul class="nav nav-pills">` section, there are five nav items.

When the `<li class="nav-consumer">` is clicked, a red border should appear around all all `<a class="consumer thumbnail">` elements. When `<li class="nav-mobile">` is clicked, a red border should appear around all the `<a class="consumer thumbnail">` elements, and so forth.

### 2.
In __app.js__, when a nav `<li>` is clicked, its class is retrieved using `.attr()` and saved into the variable `category`. If `category` is `"nav-consumer"`, first select all the `.thumbnail` elements and remove the class selected. Then select all the `.consumer` elements, and add the class selected.

### 3.
Else if category is `"nav-mobile"`, select all the .thumbnail elements and remove the class selected; then select all the .mobile elements and add the class selected.

### 4.
Else if category is `"nav-commerce"`, add the class selected to just the commerce elements.

### 5.
Else if category is `"nav-enterprise"`, add the class selected to just the enterprise elements.

### 6.
Else if category is `"nav-all"`, remove the class selected from all the `<.thumbnail>` elements.
