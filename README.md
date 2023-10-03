# Synopis Of My Daily Work Schedule As An Intern In 366Pi Technologies


## 2 August
1. First day at work at the Banglore office.
2. Then I was introduced to the team.
3. Got to know about the rules and the regulations one has to abide by in the company.
4. Had a meeting with seniors who guided me about the domain of work our company entails into.


## 3 August
1. I was introduced to a new blockchain flo-chain.
2. Referred several documentations to learn about it and its use case.
3. Got introduced to our app and its use case.


## 4 August
1. Had a meeting with vivek sir who guided me about the concept and the importance of pipelines.
2. I was introduced to docker and what is its use case.
3. Spent the rest of my time reading about docker and supervisors.
4. Referred some youtube vidoes to get an in depth analysis of the same.


## 5 August
1. Tried installind docker but was unable to due to some firewall denial of permissions.
2. Continued to browse fireship youtube channel to further explore my learnings on docker tools.
3. Got introduced to new terms like containers and docker images.
4. Learnt about the difference between the two and noted down some important commands by referring github articles that 
   could come handy in the future.

## 8 August
1. Docker installed successfully.
2. Learnt to make container with and without flags.
3. Learnt different docker commands used to read and inspect containers.
4. Studied the use case of docker and its purpose.
5. Created my own docker image.
6. Learnt the critical concept of -d command.
7. Next aim is to fully deploy an application using docker.
8. Next aim is also to deploy multiple apps at an instance using supervisor.


## 9 August
1. Learnt the use case of docker and why it is better than virtual machines.
2. Read about the use case of docker in block book.
3. Learning to deploy any application by using docker commands in a container.
4. Learning about different servers and their use case like https,dns etc:
5. Learning about nginx server.


## 10 August
1. Learnt about the supervisor commands and implemented commands like -j,-i,-q,-k etc.
2. Learnt about supervisorctl Actions ,signals and run time security.
3. In docker learning to deploy applications in containers.For that developing my own login page that uses flask,mysql on 
   the backend  and html,bootstrap and css for frontend.
4. Learning about docker compost files to deploy applications.


## 12 August
 1. Build docker image of flosight and run it as learning.
 2. Tried installing and running the blockbook manually.Faced some issues so left it at that time.
 3. Learnt the creation of docker file where the base image is not imported while the docker image is being created.
 4. Worked on my self learning project of creating a backend database storing login details of users and then to deploy 
    that finally on docker.


## 14 August
1. Tried installing blockbook again and tried to resolove errors taking help of chatgpt,bard,stack overflow.
2. Tried to learn some linux commands as it was continously required in installing such setups so thought of it as a 
   mandate to have good idea about it.
3. Worked on my self learning assigment and tried to install psql by using its docker image.

## 16 August
1. Changed my system to solve compatibility issues and reinstalled all necessary softwares.
2. Continued with my self practise of linux commands and tried the installation of blockbook again by referring to the 
   github access of ranchimall given to me.
3. Spent the next two hours in setting up psql and successfully was able to run it by using docker via Dbeaver software.
4. Researched and implemented methods for backing up and restoring data from my Dockerized database.


## 17 August
1. Designed a simple microservices architecture with multiple Docker containers.
2. Explored service discovery tools like Consul or etcd to manage communication between microservices.
3. Successfully created the docker file for the previously built docker image of flosight.


## 18 August
1. Implemented load balancing for different microservices using tools like Nginx or HAProxy.
2. Was unable to run at first instance so took some time to research on it by using tools like stackoverflow and 
   gfg(geeksforgeeks)to have a better understanding of this topic.
3. Again tried to implement blockbook installation but was stuck again by some unwanted errors on the last step of the 
   documentation that I was reffering to.
4. Ended the day in watching  some youtube vidoes that would help solving this issue.


## 19 August
1. Finished the previous backlogs and then read about my next topic CI/CD pipeline.
2. Also rewatched a teams session hosted by Abhijeet sir where I learnt about the different layers in which the whole 
   execution of transaction takes place in our app.
3. Continued my self learning on CI/CD pipelines.
4. Next aim is to set up a CI/CD pipeline using a tool like Jenkins or GitLab CI to build and test Docker images.


## 20 August
1. Was unwell so could not open lapotop in the first half of the day .
2. Installed tools like Jenkins to implement CI/CD pipelines using docker.
3. Next goal is to be able to configure automated image builds triggered by code changes in a repository.
4. Tomorrow the goal is to be able to implement CI/CD pipelines and further revise all the docker content that I have 
   previously learnt and executed.
5. Further I want to switch to linux so via virtual box would set the enviornment for that.
6. Also want to finish my self learning on Docker Orchestration with Kubernetes.


## 21 August
1. Installed ubuntu to run applications on linux.
2. Successfullly installed blockbook and was able to manually run it using the instructions posted on github.
3. Faced issue in logging into the server given via the username and the given password.
4. Henceforth would look to successfully login into the server tomorrow.
5. Then would finish my backlog activities and would convert all files till date into a single README.md file to make it 
   more presentable.


## 22 August
1. Able to do ssh in our brahmagupta server and was able to access the UI interface of blockbook from my web browser.
2. We user wget-open command to open blockbook from your ubuntu machine.
3. Set up my vs code remote explorer so that next logins are easier and less time consuming.


## 25 August
1. Figured out how you can access an app through inside a server.
2. Figured out how to access the app from outside the server through public internet.


## 26 August
1. Next task is to try dockerisng blockbook.
2. Went throught the manual steps for installation and referred chatgpt for automating these steps.


## 27 August
1. I was using the wrong base image which was not from ranchimall repository instead was taken from trezor blockbook.
2. Visited docker hub to search any other blockbook images present.
3. Also was cloning the wrong repository in my dockerfile.


## 28 August
1. Changed the base image to ubuntu latest 20.04.
2. Changed the repository from which cloning was taking place.
3. Optimised this further by using wget directly to access the deb files for backend and blockbook flo .
   

## 2 September
1. After getting the deb files I was not able to install as on performing the make-all-flo step an error of docker daemon not there was coming indicating no docker.
2. Searched up articles to solve this error and understood that here there is a docker required inside a docker.
3. Surfed stack overflow for appropriate measures to mitigate this issue.


## 3 September
1. Updated the first code version of dockerised blockbook.
2. For the deb files to be downloaded we set up a continous integration system where these steps are automated and would perform as the code is pushed into the respective     repository.


## 4 September
1. Now the files are getting installed but the systemctl command required to start both applications comprising the blockbook cannot be used.
2. Since the systemctl command is not applicable in docker so the applications are not starting .
3. Was asked to perform a 51perent attack on flo chain to test security actions.
4. Installed flo but was stuck in authenticating it.


## 5 September
1. Studied about supervisors and how it can be used to start both applications in the same container.
2. Started to prepare for my intra session on docker.


## 6 September
1. For my presentation I created a flask appliation that would on running print "hello" on the api it is hosted on through docker.
2. I also created certain python files that would show the output when it is run via docker.
3. Practised other docker commands and formalised my subtopics I wanted to cover.


## 7 September 
1. In the dockerfile for blockbook we changed the systemctl commands by accessing the actual EXEC command that runs starts the application and placed it under CMD command.
2. On building the dockerimage and on going inside the container under the -it mode ,the backend-flo application runs successfully.


## 8 September
1. The same approach failed for starting the blockbook appliacation and on putting the EXEC command under the CMD unexpected error like no file found comes up showing some 
   error that is missed.
2. Also tried to use a bash script and then to put the starting commands inside the script and call the script in the docker code .
3. This approach also failed and the applications did not start.


## 12 September
1. Started to debug my error.html file present in the blockbook docker and sought permission issues for the same.
2. Changed the user permission and relaised that two different users were using the blockbook and backend application one being the flo user and the other being the       
   blockbook-flo user.
3. The error persisted and on doing cat and ls to check the file it shows that the file exists and is not empty.

## 13 September
1. Conducted my session on docker and its implementation including several use cases.
2. Tried several methods to run docker inside a docker manually to test how it is implemented.


## 14 September
1. Made no progress and tried to explore different methods to start the applications.
2. Studied about the nature of systemd files and how commands work in it.


## 18 September
1. Found a sysbox tool through which we get an ubuntu image satisfying the requirements of docker used inside a docker container.
2. Referred documentation to complete installation steps.
3. While installing got stuck in the make step where the error says "makefile not found".


## 19 September
1. Fixed the issue and installed sysbox.
2. Also realised that the environment has to be same where we are building the image and where the deb files are installed.
3. For that we via the -it mode entered the container and then made the .deb files there inside manually to make the same environment.
4. Also since in sysbox systemd files can be used so systemctl works here and in a seperate text file we put the systemctl commands.


## 20 September
1. Blockbook was run successfully via our dockerfile.
2. Final solution is to use sysbox for making container and then to make docker in it.
3. Deployes our docker image in the docker hub and pushed the changes to github.


## 21 September
1. For improving further working on how to make more ports accessible so that better synchronization takes place of the blocks.
2. Also working on how bootstrap can be added to reudce the memory size of the built docker image.


## 22 September
 1. Updated the readme files by documenting all the steps required for implementation of blockbook.
 2. Recorded 3 videos ,2 of them uploaded on youtube showing manual demonstration of working along with one video recorded via screen recording just showing the text with
    no audio.
 3. Working on testnet environment by referring flo card's repository.


## 25 September
1. Learning the implementation of volume mounting.
2. Fixing the testnet environment for blockbook.


## 26 September
1. Build the deb files for testnet inside the docker container manually.
2. Studied the ports required for testnet network.


## 27 September
1. Successfully run the dockerfile for testnet networks.The issue was that I was using the wrong port while running the dockerfile.
2. Uploaded the  official docker image of testnet network in the docker-hub so that the user does not have to build the docker image manually.
3. Recorded a youtube video demonstrating the procedure for accessing the blockbook application through both mainnet and testnet network.


## 28 September  
1. Finished the documentation for both mainnet and testnet files.
2. Had a brief study session on CI pipelines and referred the previous files implemented for the project.
3. Project has been completed successfully and with this the internship ends.



# INTERNSHIP ENDS
   




### Documentations Link
1. https://github.com/ranchimall/flosight-docker
2. https://github.com/ranchimall/blockbook/wiki/Installing-FLO-blockbook-in-Ubuntu
3. https://github.com/docker/docs
4. https://github.com/Supervisor/supervisor
5. https://github.com/nestybox/sysbox/tree/master/docs/developers-guide
6. https://github.com/cruizba/ubuntu-dind


### Websites Link
1. https://medium.com/
2. https://towardsdatascience.com/
3. https://hub.docker.com/


### Vidoes Link
1. https://www.youtube.com/watch?v=X3Wtjwu0vBI&t=3725s
2. https://www.youtube.com/watch?v=Dlbx15qU9zE
3. https://www.youtube.com/watch?v=C-bX86AgyiA&t=103s
4. https://www.youtube.com/watch?v=tdxfbxe6r4I&t=1289s
5. https://www.youtube.com/watch?v=gAkwW2tuIqE
6. https://www.youtube.com/watch?v=Gjnup-PuquQ


### Important Linux Commands Used
1. ls - List Files and Directories: List files and directories in the current directory.
2. cd - Change Directory: Change the current working directory.
3. pwd - Print Working Directory: Display the current working directory's full path.
4. mkdir - Make Directory: Create a new directory.
5. rm - Remove Files and Directories: Delete files and directories.
6. cat - Concatenate and Display File Content: Display the content of a file.
7. more/less - Page Through Text: Display text files one screen at a time.
8. head/tail - Display the Beginning/End of Files: Display the first or last few lines of a file.
9. grep - Search Text: Search for text patterns in files.
10. find - Search for Files and Directories: Search for files and directories based on various criteria.
11. chmod - Change File Permissions: Modify file permissions (read, write, execute) for users, groups, and others.





  

