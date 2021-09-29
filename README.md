# Knowledge Graph Project

> By Venkat, Mariyam, and Harsh.

###### The following repository summarizes learnings, observations and findings carried out by the team during the tenure of the Knowledge Graph Academy training. 
###### The tools used are Apache Ni-fi, Stardog and Protege.

#### [Apache Nifi Installation](https://nifi.apache.org/docs/nifi-docs/html/getting-started.html)

Apache Nifi is an ETL tool we will be using for this project

![nifi_flow](https://user-images.githubusercontent.com/56685290/135274219-74dfcbf7-7c02-47d0-9e92-69884938b75c.PNG)


As of now installing NiFi as a service is supported only for Linux and macOS users.
For Windows users, navigate to the folder where NiFi was installed. Within this folder is a subfolder named bin. Navigate to this subfolder and double-click the run-nifi.bat file.

This will launch NiFi and leave it running in the foreground. To shut down NiFi, select the window that was launched and hold the Ctrl key while pressing C.

#### [Stardog studio](http://stardog.studio/#/)

Stardog Studio is a tool for data modelers, developers, and administrators to build and manage their data fabric.
We will be ingesting data into it from Nifi and querying the data into it using SPARQL. 
It is recommended to have a strong understanding of how to write SPARQL queries. 

[Stardog tutorial](https://www.stardog.com/tutorials/getting-started-0/)

#### Protege

There is both web and local client version available for protege. 
We recommend installing it locally as there is more documentation and tutorials available on using it.

[Protege Tutorial- Pizza ontology](https://www.michaeldebellis.com/post/new-protege-pizza-tutorial)
![Ontology](https://user-images.githubusercontent.com/56685290/135274017-bc0ec8e3-81f1-4f15-9377-542e310c11db.jpeg)
