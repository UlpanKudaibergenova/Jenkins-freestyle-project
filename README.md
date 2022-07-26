# Jenkins-freestyle-project
#### Link : https://github.com/becodeorg/DevSecOps-Training/tree/master/hill/jenkins/freestyle
### The mission
As a newly hired DevOps Engineer at a compagny called PetClinic. The company has a new website that has been written in Java. Given this Github Repo, you have been asked to make sure that the application build process (compile/test/package) works manualy in the first place (Hint: use the mvnw file inside to compile, test and package the app). Once you have done that, your mission will be to use Jenkins inside of docker (with Jenkins home folder inside the container, mounted to a locate directory) to automate to the process via a Freestyle Project in Jenkins.

### To help you achieve that goal, here are some of the steps you should go through:

-Creating a First Freestyle Project (aka Job) and Configuring It to Clone Our Git Repo

-Test if Jenkins Can Clone the Git Repo

-Fixing the Default Branch Specifier to Use Main Not the Default of Master

-Configure a Shell Build Step to Run the Maven Wrapper to Compile Our App

-Check the Job Workspace to see Jenkins Disk Based Build Operations

-Never Forget the Console Output Is Your Troubleshooting Best Friend

-Packaging Our App While Viewing Build Output in Real Time with the Scrolling Console

-Capturing App Build Artifacts: In This Case a Jar File

-Configuring Our Job to Capture Rich Unit Test Results

-Viewing Test Result Trends and Stepping through the History of Build Overviews

-Visualizing Common Build Triggers - Push, Pull, and Scheduled

-Configuring Our Job to Trigger by Polling for Changes

-Testing Our Polling Trigger by Pushing a Broken Test

-Surfacing Test Failures and Troubleshooting What Went Wrong

Github repo link : https://github.com/g0t4/jgsu-spring-petclinic

#### Jenkins Getting Started course on Pluralsight 


