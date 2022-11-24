# Devops-Project1-Steps
So, here I am sharing about my Project 1 which is "Build and Deploy .war file on Tomcat Server using simple CI/CD
pipeline."
https://github.com/arjunvip100/hello-world.git
Steps to make this Project are:-
1. Firstly, we setup Jenkins Server in EC2-instance.
2. Integrate Git with Jenkins.
3. Run Jenkins to Pull code from Github.
4. Setup Maven on Jenkins Server
-Setup Environment Variables: JAVA_HOME, M2_HOME
-install MAVEN plugin
-Configure MAVEN and Java
5. Build a Java Project using Jenkins (.war file)
6. Setup a Tomcat Server
-Setup a Linux EC2 instance
-Install Java
-Configure Tomcat
-Start Tomcat Server
-Access Web UI on Port 8080
7. Integrate Tomcat with Jenkins
- Install "Deploy to Container" Plugin
- Configure Tomcat server with Credentials
8. Deploy Artifacts on a Tomcat Server
9. Automate, Build and Deploy using Poll SCM
That's how we completely automated the whole pipeline. :)!

Watch full Procedure in this Video!
https://www.youtube.com/watch?v=fx0AFTwGSIw
