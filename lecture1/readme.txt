
Create a simple maven project and added the following information
GroupId = edu.najah
Artefact = najah
packaging = war 

after that, do the following: 

1. copy the content of pom.xml file in this site into the pom.xml file in your project
2. create a folder called WEB-INF under src/main/webapp
3. put the mouse on the newley created folder, which we have called WEB-INF in the preious step, and do right click to create a file called web.xml
4. copy the content of the web.xml file in this site to the web.xml file that you created 
5. copy the content of LoginServlet.java in this site and go to your project in eclipse, then put the mouse on src/main/java and do paste (ctrl + v) 
6. right click your porject in the project explorer of Eclipse, then choose run as >> maven build
7. under the goal field write the following
tomcat7:run






