# creditcard
Credit Card Management Java EE WebbApp

This software is only for practical demonstration purpose ; I used voluntarily different programming techiques to develop similar
things. Used technology  : Spring Core, Spring Mvc, Spring Security, Spring Tag, Jstl, Html5, JQuery, Creditly.js PlugIn (M.i.t. license),
Typeahead.js Twitter PlugIn, Hibernate, MySql Database, Logback, Web Server Target : apache-tomcat-7.0.53.

Objective : Small Credit Card Web Form user and password protected ; Save data ; Data validation ; Search data ; User Registration.

- 2 active users already exist (Administrator unsername=admin|password=123456 ; Normal User : unsername=mauro|password=123456)

- Inside "script" folder you can find mysqlDbScript.sql to generate MySql database tables. Please note that the Db name is "test".

- Inside "resources" folder you can find the db-configuration.properties, please set correct Database username and password
(now it's unsername=???|password=???)

- For the user registration section, in order to show how works a page in case of error, I voluntarily induce an exception
if you first register a user and after you try to register the same user again.