Aim: Creating an application in Dropbox to store data securely. Develop a source code using Dropbox API for updating and retrieving files. 
 
Implementation: 
1.	Go to https://www.dropbox.com/ and create an account. You can sign in with your google account. 
2.	Click on Continue with 2 GB Dropbox Basic plan at the end of the page. Create a ‘Prac6’ folder. 

3.	Go to https://www.dropbox.com/lp/developers and click on Create apps. 
 
4.	Click on generate, copy the generated access token and App key into a notepad file for later use. 
 
5.	Go to permissions and check all the following boxes. After that click on submit. 

 
6.	Go to https://colab.research.google.com/, create a new notebook and write the following code. Create a notepad file with some texts, upload it to dropbox folder ‘Prac6’.  

import dropbox dropbox_access_token= 'sl.BUTEvih4dpk6Cma3FXLv2ToJfIGwWDJ6WmruJdbLeDFVLGqoE7g_Jcmy2Yfujqz_eHH0Rr82G0gWDIASZUQgDo6co4WrbN-
YiuG5JgKiOGBRc7WlanGHglTejJhuqZ8LMLxdaWq9gvRF' 
dropbox_path= "/Prac6/aa.txt" computer_path="aa.txt" 
client = dropbox.Dropbox(dropbox_access_token) print("[SUCCESS] dropbox account linked") 
client.files_upload(open(computer_path, "rb").read(), dropbox_path) print("[UPLOADED] {}".format(computer_path)) 
 
7.	Go to https://www.wisdomaxis.com/technology/software/data/for-reports/,
get your data sample from here and also upload the excel file in dropbox folder ‘Prac6’. 
 
8.	Go to https://about.appsheet.com/, sign in with google. Create a new app. Choose the sample for the data. 

