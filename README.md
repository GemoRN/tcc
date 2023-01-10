Aim: Studying the features of the GAE PaaS model.
**Platform as a Service (PaaS) - What is it?**
PaaS is a category of cloud computing services that provide a computing platform and a 
solution stack as a service. 
Along with software as a service (SaaS) and infrastructure as a service (laaS), it is a service 
model of cloud computing. In this model, the consumer creates the software using tools 
and/or libraries from the provider/vendor. The consumer also controls software deployment 
and configuration settings. 
The provider provides the networks, servers, storage and other services. PaaS offerings 
facilitate the deployment of applications without the cost and complexity of buying and 
managing the underlying hardware and software and provisioning hosting capabilities.

**PaaS Key Features**
1. Services to develop, test, deploy, host and maintain applications in the same 
integrated development environment 
2. Web-based management/administration consoles 
 Reducing the need for system administration/dev ops 
 Resource utilization monitoring capabilities 
 Easily identify bottlenecks 
 Multi-tenant architecture 
 Certain PaaS offerings attempt to support use of the application by many 
concurrent users, by providing concurrency management, scalability, fail-over and 
security 
 Support for development team collaboration 
 Pay for what you use billing model Stop
**PaaS - Popular offerings**
**Heroku** 
One of the first cloud platforms, has been in development since June 2007, when it 
supported only the Ruby programming language, but has since added support for Java, 
Node.js, Scala, Clojure, Python and (undocumented) PHP 
**Windows Azure **
Microsoft's cloud computing platform used to build, deploy and manage applications 
through a global network of Microsoft- managed datacenters 
**dotCloud **
Founded in 2008 by Solomon Hykes, dotCloud is the first application platform 
designed from the ground up for modern service-oriented development 


**Cloud Foundry **
• Developed by VMware released under the terms of the Apache License 2.0 
• Primarily written in Ruby 
• AppCloud runs on Cloud Foundry 
• Since it is open sourced, ActiveState has created a commercial distribution of the 
Cloud Foundry software for enterprises to host their own private PaaS
**Engine Yard **
A San Francisco, California based, privately held platform as a service company 
focused on Ruby on Rails and PHP, and recently announced support for Node.js deployment 
and management 
**Google App Engine (often referred to as GAE or simply App Engine, and also used by 
the acronym GAE/J) **
• A cloud computing platform for developing and hosting web applications in Googlemanaged data centers 
• Applications are sandboxed and run across multiple servers 
• Offers automatic scaling for web applications-as the number of requests increases for 
an application, App Engine automatically allocates more resources for the web 
application to handle the additional demand 
• Is free up to a certain level of consumed resources. Fees are charged for additional 
storage, bandwidth, or instance hours required by the application 
• First released as a preview version in April 2008, and came out of preview in 
September 2011
**What is Google App Engine?**
Google App Engine lets you run web applications on Google's infrastructure. App Engine 
applications are easy to build, easy to maintain, and easy to scale as your traffic and data 
storage needs grow. With App Engine, there are no servers to maintain: You just upload your 
application, and it's ready to serve your users.
**The Application Environment**
Google App Engine makes it easy to build an application that runs reliably, even under heavy 
load and with large amounts of data. App Engine includes the following features; 
• Dynamic web serving, with full support for common web technologies 
• Persistent storage with queries, sorting and transactions 
• Automatic scaling and load balancing
• APIs for authenticating users and sending email using Google Accounts 
• A fully featured local development environment that simulates Google App Engine on 
your computer 
Your application can run in one of three runtime environments: the Go environment, the Java 
environment, and the Python environment, which gives you a choice of Python 2.5 or Python 
2.7
**Why App Engine? **
Pros 
• Easy to Get Started 
• Automatic Scalability 
• The Reliability, Performance, and Security of Google's Infrastructure 
• Costs less 
• There is a generous free usage quota and you only pay for what you use 
Cons 
• Sandboxed environment limits the scope of your application 
• Although we can pay for certain additional resources, there are some that have a hard 
limit
Traditional Way 
1. Write your code • • • • 
2. Configure & Deploy Web server (Apache/Tomcat) 
3. Configure & Deploy SQL database 
4. Maintain all of these infrastructure 
5. Cost of building and maintaining the infrastructure
**App Engine Way **
1. Write your code 
2. A set of simple configurations to let App Engine know how to serve your application 
Tools Bundled with the SDK 
Development Server 
Uploading and Managing an App 
Uploading and Downloading Data 
ProtoRPC 
webapp Framework 
Local Unit Testing 
Appstats 
Included Libraries (Python 2.5) 
• Django, PyCrypto, YAML, zipimport 
Included Libraries (Python 2.7) 
• Jinja2, PIL, webapp2, etc QBurst I meet.google.com is sharing your screen.
