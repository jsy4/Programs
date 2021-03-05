# Changes for Lab1
* L1: fork and clone to local computer. Programs had /Circles, /Coverage, /SimpleWebServer with /src and package struct as edu.nmsu.cs...
* Changes made:
	* Hello: added project folder /HelloWorld with /src and package struct, added file called helloworld.java under /HelloWorld
	* Questions: added new folder in root dir named /Questions, added 2 .txt to /Questions named p1Questions.txt, p2Questions.txt 
	* Ant Buildfiles: made build.xml for /Circles, /SimpleWebServer and touched
	* readMe: updated.
	_forked from toupsz_
	* MyID: jsy4

:upside_down_face: https://github.com/jsy4/Programs


# Programs
Base code for program assignments in Software Development (C S 371). 

## Program 1 and Program 2
These assignments rely on the SimpleWebServer program. Each gets graded using tags in a cloned repository.

* Changes made for Program 1: 
	* Webworker.java: serves HTML files according to GET request from the url. Checks if the file exists and displays the HTML file(200.OK) or defaults to HTML page displaying error with status code 404. When reading and outputing HTML, it substitutes tags. 
	* build.xml: updated to <ant> (default: clean, compile) and <ant run> (runs program on port 8080) 
	* p1.Questions.txt are answered.
	* readMe: updated.

* Changes made for Program 2:
	* WebServer is now changed to serve image file types GIF, JPEG, PNG.
	* www subfolder: has the image files that are less than 10KB (jpgTest.jpg, pngTest.png, gifTest.gif, favicon.ico). It also contains two test HTML files test1.html, test2.html, and these files in www uses the image files using html img tag. Also included /res/acc/test.html for testing in www subdirectory.
	* build.xml: the ant command itself will now clean, comiple, run. ant gets the source code from the root directory SimpleWebServer and runs the code in subdirectory www, creating bin directory there to run.
	* p2.Questions.txt are answered.
	* readMe: updated.


## Program 3
This assignment relies on the Coverage programs. 

## Program 4
This assignment relies on the Circles programs. 
