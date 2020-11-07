# devops-pipeline-for-my-personal-website

Finding it necessary to always update my personal website  to match my profile, I decided to create a proof of concept for a devops pipeline using JENKINS, MAVEN ,ANSIBLE and GIT for a HELLO-WORLD java project and later updating the pipeline to use it for my own project since python dosen't require building but might benefit from a devops pipeline.

To keep my own enviroment clean I decided to use AWS EC2  in order to create different instances which helps me seperate concerns and solve and debug problems much faster !


JENKINS server : http://52.90.22.13:8080/

TOMCAT server : http://54.161.138.8:8080/

user : admin 

password: pwd

(I do realize  that giving admin access to visitors is a bad idea that is why I'm going to configure  user groups in JENKINS in order to limit priveleges for people that wants to just checkout mu work)
