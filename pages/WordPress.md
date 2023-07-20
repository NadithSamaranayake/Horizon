-
- portal localhost:8080
## Installing WordPress
	- download xampp and install it
	- run xampp and start the apache and mysql servers
	- click on admin
	- if there is error saying portal not found watch this video and change the portal number
	- {{video https://www.youtube.com/watch?v=N9ajthBX_1Y&ab_channel=TheGeekPage}}
	- after launching phpmyadmin create a database and give a name to it
	- after setting these things up, go to this site and download wordpress
		- https://wordpress.org/download/
	- after downloading, extract the folder
	- go to the location where xampp is installed and click on **htdocs** folder
	- create a new folder inside htdocs and copy the files which were in the extracted wordpress setuop file into the new folder in htdocs
	- open the web browser and type **localhost/(new folder name)/**
		- if there was an port error, type in the port number (localhost:8080/(foldername)) and then login
	- install wordpress. (admin1234)
## What is Web Design?
	- Web design governs everything involved with the visual aesthetics and usability of a website -- color scheme, layout, information flow, and everything else related to the visual aspects of the UI/UX (User Interface and User Experience)
## Content Management System (CMS)
	- CMS provided an organization with a way to manage digital information on a website through creating and maintaining content without prior knowledge of web programming or markup languages.
	- Some content management systems are free , such as;
		- Drupal
		- Joomla
		- WordPress
## What is WordPress
	- WordPress is a free and open source content management system written in PHP and paired with a MySQL or MariaDB database. Features include a plugin architecture  and a template system, referred to within WordPress as themes.
- after launching localhost:8080/myweb a website will be shown
- to get to the wordpress dashboard click on the url and type /wp-admin in the end and press enter
- ## Resetting the website
	- go to plugins
	- add plugin
	- type reset on the search bar
	- install wp-reset plugin