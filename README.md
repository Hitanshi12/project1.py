Project Description



This project is about docker. Now the question comes what is docker?  Basically , Docker is a set of platform as a service (PaaS) products that uses OS-level virtualization to deliver software in packages called containers. Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels. All containers are run by a single operating system kernel and therefore use fewer resources than virtual machines. 

 Docker uses a technique called containerization. And docker is a tool of container engine. Docker was developed by Solomon Hykes in 2013.Docker  is basically known for launching operating system in just one second. They are not actually operating system but they are containers because they contain applications. They have their own IPAddress. 
                                
                                
Some pre requisite for using docker :

1. You should have RedHat (linux) in your system.
2. You should have the knowledge of some general commands in linux.
3. yum should be configured for docker.


e.g.=

		  [docker]
 
	  	baseurl=https:///download.docker.com/linux/centos/7/x86_64/stable/

      gpgcheck=0

              


Guidelines to run the project:

1. Install python3 in your RedHat.

e.g.=


[root@localhost ~]# yum install python3


Repository 'docker' is missing name in configuration, using id.


Repository 'dvd1' is missing name in configuration, using id.


Repository 'dvd2' is missing name in configuration, using id.

^Cdocker                   [===                 ] ---  B/s |   0  B     --:-- ETdocker                                          0.0  B/s |   0  B     00:00    







 
2. Run "python3 project.py" to run this project


3. This screen will appear to you.

       hey welcome to my project!!!
			******************************

        press 1: For installing Docker
        press 2: For pulling centos image
        press 3: For launching OPerating system (centos)
        press 4: For docker help
        press 5: For creating docker image of your operating system
        press 6: For uploading your docker image
        press 7: For starting your os
        press 8: For creating your own volume  in docker 
        press 9: To check volume
        press 10:To attach your storagge in os
        press 11:For installing docker-compose
        press 12:For pulling ubuntu image
        press 13:For launching os (ubuntu)
        press 14:
        
        press 0: For exit

        
Enter your choice:




 
4. Enter your choice.

Some important points:

1. Before installing docker , yum must be configured.
2. Before creating an docker image , you must have at least one os launched.
3. Without installation of python , the project won't able to run.
4. Launched container will look like:

       Enter your choice:3
       
       
       
       tell me the  name which  you would like to give your os:os3


 

        [root@9d0d9052419b /]# 



 

Links for reference:

1. For docker-ce installation:

https://download.docker.com/linux/centos/7/x86_64/stable/Packages/

2. For installing docker-compose:

a. curl -L "https://github.com/docker/compose/releases/download/1.25.5/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

b. chmod +x /usr/local/bin/docker-compose

