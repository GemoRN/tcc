Practical no 9
Aim: Configuring and deploying VMs/Dockers using Chef/Puppet Automation tool 
 https://www.chef.io/downloads/tools/workstation?os=windows&_gl=1*1sj0jq*_ga*NDIxNDY1NzExLjE2NzMzNjU2NjA.*_ga_9JSNBCSF54*MTY3MzM3NDQ0OC4zLjAuMTY3MzM3NDQ0OS41OS4wLjA.


Implementation: 
1.	To install Chef workstation, search on google for ‘chef workstation windows setup’ and select the first link 
2.	Select the windows downloads page and download the most stable version of the installer 
3.	Run the downloaded MSI installer and once finished, open the cw powershell and type ‘chef’ on your cmd to verify 
4.	Enter the following command 

Chef generate cookbook admin 

5.	Type tree once done to see your file structure 
6.	Now type the following commands 

chef gem install kitchen-docker 

7.	Go to the directory of the admin cookbook and edit the kitchen.yml file as follows 

Driver: 
      Name: docker 

Transport: 
      Name: docker 

Platforms: 
      -name: exec  Driver: 
       Name: exec 
       -name:exec 
       
8.	Now type the following commands 

>kitchen create 

>kitchen list 

>kitchen converge 

>kitchen list 
