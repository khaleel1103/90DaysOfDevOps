## Day 29 Task: Jenkins Important interview Questions.

 <p align="center"><img align="center" src="https://user-images.githubusercontent.com/115981550/215283081-1c77ac18-4825-49d1-8727-7f0940846fff.png" /></p>
 

## Jenkins Interview
 Here are some Jenkins-specific questions related to Docker that one can use during a DevOps Engineer interview:
 
## Questions

1. What’s the difference between continuous integration, continuous delivery, and continuous deployment?
Ans: Continuous Integration is the practice where developers merge the changes to the code base to the main    branch as often as possible. These changes are validated by creating a build and then running automated tests against the build. If these tests don’t pass, the changes aren’t merged, and developers avoid integration challenges that can happen.
Continuous Delivery is an extension of CI since it enables automation to deploy all the code changes to an environment (dev, qa, stage, prod, etc) after the changes have been merged. The artifact may be built as part of CI or as part of this process since the source of truth (your repository) is reliable given your CI process. In simple terms, this means that there is an automated release process on top of the automated testing process and that developers can deploy their changes at any time by simply clicking a button or at the completion of CI.
Continuous Deployment takes the process one step further than continuous delivery. Here, all changes that pass the verification steps at each stage in the pipeline are released to production. This process is completely automated and only a failed verification step will prevent pushing the changes to production.
2. Benefits of CI/CD
Ans: The primary goal of a CI/CD pipeline is to deliver working software to users quickly and frequently.
3. What is meant by CI-CD?
Ans: CI and CD stand for continuous integration and continuous delivery/continuous deployment. In very simple terms, CI is a modern software development practice in which incremental code changes are made frequently and reliably. Automated build-and-test steps triggered by CI ensure that code changes being merged into the repository are reliable. The code is then delivered quickly and seamlessly as a part of the CD process. In the software world, the CI/CD pipeline refers to the automation that enables incremental code changes from developers’ desktops to be delivered quickly and reliably to production.
4. What is Jenkins Pipeline?
Ans: Jenkins Pipeline (or simply "Pipeline") is a suite of plugins which supports implementing and integrating continuous delivery pipelines into Jenkins. A continuous delivery pipeline is an automated expression of your process for getting software from version control right through to your users and customers.
5. How do you configure the job in Jenkins?
Ans: Step 1 − Go to the Jenkins dashboard and Click on New Item.
     Step 2 − In the next screen, enter the Item name, in this case we have named it Helloworld. Choose the ‘Freestyle project option’.
     Step 3 − The following screen will come up in which you can specify the details of the job.
     Step 4 − We need to specify the location of files which need to be built. In this example, we will assume that a local git repository(E:\Program) has been setup which contains a ‘HelloWorld.java’ file. Hence scroll down and click on the Git option and enter the URL of the local git repository.
     Step 5 − Now go to the Build section and click on Add build step → Execute Windows batch command
     Step 6 − In the command window, enter the following commands and then click on the Save button
     Step 7 − Once saved, you can click on the Build Now option to see if you have successfully defined the job.
     Step 8 − Once the build is scheduled, it will run. The following Build history section shows that a build is in progress.
     Step 9 − Once the build is completed, a status of the build will show if the build was successful or not. In our case, the following build has been executed successfully. Click on the #1 in the Build history to bring up the details of the build.
     Step 10 − Click on the Console Output link to see the details of the build.
6. Where do you find errors in Jenkins?
Ans: Mostly error can be seen in the console output where we see the reson of the failure to trouble shoot the error.
some of the comman resons are like 
1) we didnt provide the proper git repo url.
2) sshagents not configered properly.
3) Commands error.
etc....
7. In Jenkins how can you find log files?
Ans: /var/log/jenkins/jenkins.logs
8. Jenkins workflow and write a script for this workflow?
Ans: yes i can.
9. How to create continuous deployment in Jenkins?
Ans Code is Constructed-conduct unit test- conduct system testing - Deliver to staging environment-Conduct user Acceptance Tests-Deploy to Production.
10. How build job in Jenkins?
Ans: Building the Job in Jenkins by intergrating with the git where you will Pull the code and using the differnt building tools such as Mavin,ant,gradle we can Build the code.
11. Why we use pipeline in Jenkins? 
Ans: Jenkins pipeline make the devolper and Opertions good Bonding and it makes all the thing automate.it can be run in the loop,Since Jenkins pipeline is written in code, any number of users can use it as a template, modify it and run customized tests and processes,Multiple jobs can be run in parallel.
12. Is Only Jenkins enough for automation?
Ans: Yes its enough with pluging intergrated and also we have similar tools.
13. How will you handle secrets?
Ans some of the comman ways Privileged account credentials
Passwords,Certificates,SSH keys,API keys,Encryption keys
14. Explain diff stages in CI-CD setup
Ans: The trigger--Code checkout--Compile the code--Run unit tests--Package the code--Run acceptance tests--Delivery or Deployment
15. Name some of the plugins in Jenkin?
Ans:git,sonarqube,docker.sshagent,Maven Intergrstion,Amazon EC2,Build pipeline,Mailer,jenkiens backup.



These questions will help you in your next DevOps Interview.
Write a Blog and share it on LinkedIn.

*Happy Learning :)*
