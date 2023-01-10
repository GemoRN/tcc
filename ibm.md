Practical No. 7 
Aim: Cloud application development using IBM Bluemix Cloud. 
 
Implementation: 
1.	Log in to IBM Cloud at cloud.ibm.com. 
2.	Go to the catalog (cloud.ibm.com/catalog). 
 
3.	Click the Node-RED boilerplate and fill in the required data to create an instance. 
 
4.	Specify an app name and click Create. 
 
After the process completes, the environment is ready to use. When you access the IBM Cloud dashboard, the Node-RED instance is in Running state. 
 
5.	Click Overview on the left to access the application information. The information instance is displayed. 
 
If you named the app app101-node-red, its route would be: http://app101-node-red.mybluemix.net. 
6.	To modify this app to meet your requirements, you need to have access to its code. IBM Cloud provides a way to allocate space in a GIT repository, where you can access application code and files. Create this space by clicking Enable, located in the lowerright corner, and then Create in the next panel. 
When the process finishes, you see the Toolchain. 
 
7.	To access the code, click Eclipse Orion Web IDE, select your application on the lefthand side, and then click the public directory. 
 
8.	To set up your app, you need to add and modify these files in the public directory: 
•	cloud.html 
•	d3.layout.cloud.js 
•	d3.v3.min.jsDownload these files to your workstation from GitHub at https://github.com/barabasj/Bluemix-App. 
9.	Upload the files to the GIT repository by clicking File > Import > File or Zip Archive. 
 
10.	After you upload all the files, you need to publish all of the contents of the GIT repository to the running instance on IBM Cloud. 
 
To deploy the changes, press the arrow button. Another option is to enable the LiveEdit switch to deploy every change in auto mode. 
 
You see a (deploying) state while it is processing. 
 
When the deployment process finishes, the green sign shows (running: normal) again. 
 
11.	To create the Node-RED app that will feed the cloud.html file that you just uploaded and deployed, open the Node-RED editor in the browser by clicking the Link to Application icon Welcome panel to access the deployed application. 
12.	The first time you run a Node-Red instance, you need to specify its properties. On the first panel, click Next. 
 
13.	Enter your username and password, and click Next. 

 
14.	Read through the general information panel, and click Next. 
 
15.	Click Finish to complete the installation. Your configuration is saved and the Node-Red instance starts. 
16.	Select Go to your Node-RED flow editor to access the Workflow Editor. Notice your application URL: {your-instance-name}.mybluemix.net. 
17.	Enter your username and password and click Login to open the flow editor. 
The left-hand nav bar contains all of the tools, services, and functions that you need to compose IBM Cloud apps inside the Node-RED environment. Using the simple drag-anddrop interface, you can build just about any complex app you like. In addition, you can import and export complex code to transfer and reuse. You can use this process to populate your app quickly and easily. 
18.	One of the files in the GitHub repo mentioned above is wordcloud.txt. This file contains the text that's exported from the app that you are creating. Select and copy the contents of wordcloud.txt
 
19.	Next, click Import > Clipboard in the Node-RED editor.  
The objects that represent the application are shown in the following image: 
20.	You need to configure some nodes in order to get the application to work. The flow starts reading public tweets accessed by a personal account, filtering the results with a trending topic that ensures that you have matches to be processed by your app. Open the first node (Twitter input): 
The help information is displayed on the right: 
21.	Open the Twitter node by double-clicking on it.  
22.	Enter your Twitter ID and any topic you want to display. You can obtain better results by specifying Trending Topic. 
To exclude all non-significant words from the resulting tweets, depending on the language of the matching tweets, you can update the "Count words in array" function node (line 3) to reflect the selected ones. The variable "garbage" must contain all words selected to be ignored by the counters. 
 
23.	To publish the changes, click Deploy in the upper right. 
 
Every time a change to an object is made, a little dot is displayed on the node. Once the app has been deployed, the dot disappears. 
 
To debug your app and display the processed tweets, a debug node has been added to the flow: 
 
Matching tweets are displayed in the debug window of the GUI: 
 
24.	To display the word cloud created by the app, access the following URL: http://_<app_name>_.mybluemix.net/cloud.html. 
