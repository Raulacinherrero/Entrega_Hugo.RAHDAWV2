---
title: "Client"
date: 2022-10-24T16:06:18+01:00
draft: false
weight: 1
---

Each time you jump between pages, depending on parameters you have given, or information contained in the database, PHP may build a different version of the same page. You want the page itself to respond to events you perform while you're on it, to behave like a general-purpose program. It's JavaScript, all browsers understand it. With Javascript you can handle all events and make your web page act dynamically.

It allows you to directly manipulate HTML elements and modify their state, shape, color, position, and various properties. The Javascript code is embedded within HTML. Of course, if you generated your page with PHP, it in turn allows you to generate JavaScript code, which is something that the browser understands along with HTML. In the end, at runtime, the user interacts directly only with the code written in JavaScript.

With these 3 tools, we can create a really powerful website. Well let's just say that it takes a while to understand the "execution order" of a web page. If you notice, the communication with the database server...is in PHP. It is executed on the server that contains the DB and only through PHP code, and all this is done before loading the page in your browser.

In other words, JavaScript is as nice and dynamic as you want it to be, but it can't communicate with the database. If I ask my website for certain data from my database, using JavaScript, it cannot give it to me. That way, I can't dynamically update my web elements, at least through the Database. One option would be to call a new page, according to those parameters, and the whole process would be done again, starting by creating the new page with PHP based on the query.

Every time I request something from the database, Javascript would call a new page that does the work using PHP.