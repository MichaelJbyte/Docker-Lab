# Docker-Lab
Short lab to get hands on with Docker software.
3/7/25

This lab was conducted alongside a video on youtube providing hands on experience with Docker, a platform dedicated to the use of containers. The lab was brief and gave my first hands-on experience with container software. The experience taught me how to create, view, and manage containers. All of this was completed through Linode.

## Below will be the steps I took when following the hands on lab:

1. Generated a Docker linode session via Linode.
___________________________________________________________________________
 ![image alt](https://github.com/MichaelJbyte/Docker-Lab/blob/e5a14398c1b42efbb6eace8a851a56c313988344/Docker%20001.png)
___________________________________________________________________________
2. Pulled the centos OS from the simulated Docker terminal.
    - Used: "docker pull centos"
3. Created a centos container and named it.
    - Used: "docker run -d -t --name dockercontainerOne centos"
4. Opened my newly created container. This initiated another terminal which could be used in the new container.
    - Used: "docker exec -it dockercontainerOne bash"
___________________________________________________________________________
![image alt](https://github.com/MichaelJbyte/Docker-Lab/blob/e5a14398c1b42efbb6eace8a851a56c313988344/Docker%20002.png) 
___________________________________________________________________________
[I repeated the steps above for two more distributions such as Alpine and Ubuntu Linux.]

  - I also utilized "hub.docker.com" to find an already established container and run.
___________________________________________________________________________
![image alt](https://github.com/MichaelJbyte/Docker-Lab/blob/e5a14398c1b42efbb6eace8a851a56c313988344/Docker%20003.png) 
______________________________________________________________________________

# Afterthoughts

Overall this small lab taught me the basics of how to easily create containers and showed me how to manage them. It also demonstrated
to me why they are being used as a better option as opposed to virtual machines. Containers are handled much quicker than VM's and 
they are even isolated, unlike VM's.
