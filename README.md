# Referrers-Tracker-traffic-analyze-link-exchange
This free HazratSultanBahu Referrers Script provides two options. On the one hand you can analyze who send traffic and refer visitors to your website including how many times and on the other hand you can use it as link exchanger to display and track link exchange. You can display links in html, php and all other formats and extensions.

HAZRATSULTANBAHU REFERRERS tracker Script Version 1.1
-----------------------------------------------------
Free scripts https://www.hazratsultanbahu.com/scripts/

Features:-
----------

Referrers Tracker
-----------------
•	It track referrers to your site (from which web visitor come to your website) 
•	How many times 
•	It display number of hits from referrer web to your web
•	It also display number of hits from your web to referrer web

Link exchanger 
--------------
•	You can use this script as link exchanger 
•	You can display links of other web who display your web link in their web
•	This script can show your approved links of other web in your web page 
•	It can also show all links with auto approval 
•	You can set, after how many clicks from other web it display that web link in your web page

Display links in other than php web pages
-----------------------------------------
•	You can add links in html, htm and other web page including php

Installation 
------------
1.	Unzip referrers.zip in your computer / laptop
2.	Access your web hosting files with FTP or file manger 
3.	Create referrers folder under your web public_html folder (files need to be transfer in /public_html/referrers/)
4.	Transfer all files of referrers folder of your computer / laptop folder in created web new referrers folder (transfer files not referrers directory)
5.	Create new 
a.	database 
b.	database user 
c.	password
d.	(if you don’t understand how create database, database user name, password learn from this link https://www.hazratsultanbahu.com/scripts/how-to-create-a-database-and-user.php)
6.	Access yourdomain.com/referrers/ fallow instructions and install you can also access install with yourdomain.com/referrers/install.php (you must replace your own domain in place of yourdomain.com to access installations)

How use it
-----------
Add this code 

<?php
include ($_SERVER['DOCUMENT_ROOT'] . '/referrers /log.php');
?>

in any your web php page to track referrer, it will only track that page which has this code, add in page top first line
(Don’t add this code in that web page which shows referrers web links)

See yourdomain.com/referrers/example.php (you must replace your own domain in place of yourdomain.com to access THIS PAGE)

To show referrers approved web links
------------------------------------
Add this code in any your web php page

<?php
include ($_SERVER['DOCUMENT_ROOT'] . '/referrers /approved-referrers.php');
?>

To show random referrers approved web links
-------------------------------------------
Add this code in any your web php page

<?php
include ($_SERVER['DOCUMENT_ROOT'] . '/referrers / approved-random-referrers.php');
?>

To show all referrers web links with out approval 
-------------------------------------------------
Add this code in any your web php page

<?php
include ($_SERVER['DOCUMENT_ROOT'] . '/referrers / all-referrers.php');
?>

To show referrers approved web links in html page
-------------------------------------------------
If you want to show approved referrers web links in html page instead of php page add this code in your any web page

<object width="300" height="300” type="text/plain" data="/referrers/referrers.html" border="0" > </object>

Or

<iframe src="/referrers/referrers.html" frameborder="0" height="100%" width="100%"></iframe> 

(Change width="100%" height="100%” as per your need)

For Help and support please visit https://forum.hazratsultanbahu.com/forum/index.php/board,33.0.html
