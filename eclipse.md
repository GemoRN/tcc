Practical no 01
 Open Eclipse IDE and create a new Maven project 
1.	Select the catalog as internal and below that select the last option of the list mentioning ‘web_app’ and click ‘Next’ 
2.	Enter the group_id: com.udcs and artifact_id: firstwebapp 
 
3.	Open pom.xml and edit to match the following 
	 	 
5. Go to web.xml in src/main/webapp/web-inf and edit it as shown below <web-app 
6. Right click on web-inf and create XML file named ‘spring-web-servlet.xml’ and edit as follows 
 
7.	Create new folder in WEB-INF as ‘views and a subfolder as ‘jsp’ and create a ‘hello.jsp’ file in it as follows 
 
8.	Right click on src/main/resources in the file explorer and create new folder named ‘java’ but select ‘main’ in the folder creating wizard before that 
9.	Create a java class in java folder named ‘hellocontroller.java’ as shown below 
 
10.	Edit HelloController.java as follows import java.util.regex.Matcher; 
11. Edit the ‘hello.jsp’ file as follows mySelection = app.activeDocument.selection; myDoc = } 
12.	In IDE, right click on firstwebapp > Maven > update Project > check on ‘force update snapshot’ > Finish  
13.	Right click on project > run as > Maven build 
14.	In the following pop-up, enter the goals as ‘clean install’ 
15.	Right click on project > Run as > Run on server > Apache Tomcat v9 > select any file in configured > Finish  To see the output 
	
	
	
https://www.eclipse.org/downloads/download.php?file=/oomph/epp/2022-12/R/eclipse-inst-jre-win64.exe&mirror_id=1281

https://archive.apache.org/dist/tomcat/tomcat-7/v7.0.32/bin/apache-tomcat-7.0.32-windows-x64.zip

create malven project 

org.apache.malven.archtypes

