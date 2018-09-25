# Referrers-Tracker-traffic-analyze-link-exchange
This free HazratSultanBahu Referrers Script provides two options. On the one hand you can analyze who send traffic and refer visitors to your website including how many times and on the other hand you can use it as link exchanger to display and track link exchange. You can display links in html, php and all other formats and extensions.

HAZRATSULTANBAHU REFERRERS tracker Script Version 1.1
-----------------------------------------------------
Free scripts https://www.hazratsultanbahu.com/scripts/

Features:-
----------

Referrers Tracker<br>
-----------------<br>
• It track referrers to your site (from which web visitor come to your website)
<br>
• How many times <br>
• It display number of hits from referrer web to your web<br>
• It also display number of hits from your web to referrer web<br>
<br>
Link exchanger <br>
--------------<br>
• You can use this script as link exchanger <br>
• You can display links of other web who display your web link in their web<br>
• This script can show your approved links of other web in your web page <br>
• It can also show all links with auto approval <br>
• You can set, after how many clicks from other web it display that web link in 
your web page<br>
<br>
Display links in other than php web pages<br>
-----------------------------------------<br>
• You can add links in html, htm and other web page including php<br>
<br>
Installation <br>
------------<br>
1. Unzip referrers.zip in your computer / laptop<br>
2. Access your web hosting files with FTP or file manger <br>
3. Create referrers folder under your web public_html folder (files need to be 
transfer in /public_html/referrers/)<br>
4. Transfer all files of referrers folder of your computer / laptop folder in 
created web new referrers folder (transfer files not referrers directory)<br>
5. Create new <br>
a. database <br>
b. database user <br>
c. password<br>
d. (if you don’t understand how create database, database user name, password 
learn from this link 
<a href="https://www.hazratsultanbahu.com/scripts/how-to-create-a-database-and-user.php">
https://www.hazratsultanbahu.com/scripts/how-to-create-a-database-and-user.php</a>)<br>
6. Access yourdomain.com/referrers/ fallow instructions and install you can also 
access install with yourdomain.com/referrers/install.php (you must replace your 
own domain in place of yourdomain.com to access installations)<br>
<br>
How use it<br>
-----------<br>
Add this code <br>
<br>
<code>
&lt;?php
include ($_SERVER['DOCUMENT_ROOT'] . '/referrers /log.php');
?&gt;</code>
<br>
<br>
in any your web php page to track referrer, it will only track that page which 
has this code, add in page top first line<br>
(Don’t add this code in that web page which shows referrers web links)<br>
<br>
See yourdomain.com/referrers/example.php (you must replace your own domain in 
place of yourdomain.com to access THIS PAGE)<br>
<br>
To show referrers approved web links<br>
------------------------------------<br>
Add this code in any your web php page<br>
<br>
<code>
&lt;?php
include ($_SERVER['DOCUMENT_ROOT'] . '/referrers /approved-referrers.php');
?&gt;</code>
<br>
<br>
To show random referrers approved web links<br>
-------------------------------------------<br>
Add this code in any your web php page<br>
<br>
<code>
&lt;?php
include ($_SERVER['DOCUMENT_ROOT'] . '/referrers / 
approved-random-referrers.php');</code>
<br>
?&gt;<br>
<br>
To show all referrers web links with out approval <br>
-------------------------------------------------<br>
Add this code in any your web php page<br>
<br>
<code>
&lt;?php
include ($_SERVER['DOCUMENT_ROOT'] . '/referrers / all-referrers.php');
?&gt;
</code>
<br>
<br>
To show referrers approved web links in html page<br>
-------------------------------------------------<br>
If you want to show approved referrers web links in html page instead of php 
page add this code in your any web page<br>
<br>
<code>
&lt;object width=&quot;300&quot; height=&quot;300” type=&quot;text/plain&quot; 
data=&quot;/referrers/referrers.html&quot; border=&quot;0&quot; &gt; &lt;/object&gt;
</code>
<br><br>
Or<br>
<br>
<code>
&lt;iframe src=&quot;/referrers/referrers.html&quot; frameborder=&quot;0&quot; height=&quot;100%&quot; 
width=&quot;100%&quot;&gt;&lt;/iframe&gt;</code>
<br>
<br>
(Change width=&quot;100%&quot; height=&quot;100%” as per your need)<br>
<br>
For Help and support please visit 
<a href="https://forum.hazratsultanbahu.com/forum/index.php/board,33.0.html">https://forum.hazratsultanbahu.com/forum/index.php/board,33.0.html</a> </p>
