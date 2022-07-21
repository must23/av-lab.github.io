---
title: Back-end & Front-end Development
layout: page
permalink: /tutorials/sys3
exclude: true
---

# Install a web server on the cloud

The **LAMP stack** is a popular [open-source solution stack](https://phoenixnap.com/glossary/what-is-open-source) used primarily in web development.

LAMP consists of four components necessary to establish a fully functional web development environment. The first letters of the components' names make up the LAMP acronym:

* **Linux** is an operating system used to run the rest of the components.
* [**Apache** **HTTP Server**](https://phoenixnap.com/kb/install-apache-on-centos-7) is a web server software used to serve static web pages.
* **MySQL** is a [relational database management system](https://phoenixnap.com/kb/what-is-a-relational-database) used for creating and managing web databases, but also for [data](https://phoenixnap.com/kb/best-database-software)[warehousing](https://phoenixnap.com/kb/data-warehouse-architecture-explained), application logging, e-commerce, etc.
* **PHP, Perl, and Python** are programming languages are used to create web applications.

Each component represents an essential layer of the stack. Together, the components are used to create database-driven, dynamic websites.

 Follow the following instructions from AWS documentation to install a web server on your AWS instance.
*  [Install LAMP on Amazon Linux 2022](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-lamp-amazon-linux-2022.html)


# Front-end Development
To refresh your knowledge on front-end development, you may go through the 4 part crash course:
* Part 1
<iframe width="560" height="315" src="https://www.youtube.com/embed/O9Uauq-Gd0c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

* Part 2
<iframe width="560" height="315" src="https://www.youtube.com/embed/d5HnAlAFt40" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

* Part 3
<iframe width="560" height="315" src="https://www.youtube.com/embed/SkuHUUyCKIw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

* Part 4
<iframe width="560" height="315" src="https://www.youtube.com/embed/5OCrKVNqCcs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>


# Back-end Developmpent
Back-end refers to the server side of web development. In other words, the server can serve multiple clients (or computers). Although HTML/CSS/JS provides a rich user interface, it runs entirely on clients' machines; in other words, it is completely decentralized and agnostic of other clients, which is a limiting factor. What if you want to perform some computation that relies on multiple clients? Say you want to show how many items are available in stock based on online customer records. Then you would need a `server` that aggregates the computation. LAMP is software stack that allows performing that using PHP language along with MySQL database. 
* Enter your AWS server
* Follow video below `Learn PHP in Under 15 Minutes!`

<iframe width="560" height="315" src="https://www.youtube.com/embed/ysJjgzcZOPY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

For more in-depth tutorial, you may follow [W3 School tutorial](https://www.w3schools.com/php/default.asp).

## Optional
If you finish LAMP early, you may try [Django framework that allows python  for backend development using python](https://www.w3schools.com/django/)
* [Install Django server on your EC2 instance ](https://docs.djangoproject.com/en/4.0/topics/install/)
* [Go through Django tutorials](https://www.w3schools.com/django/)