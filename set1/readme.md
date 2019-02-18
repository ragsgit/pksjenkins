In this version, Jenkins pod comes up, but doesn't get the projects from the previous run.
Steps: Create SC, PVC, deploy pod, and define service.
Lauch Jenkins browser, create projects, 
Check projects is JENKINS_HOME/.jobs folder
Delete POD
Deploy POD again (uses same PVC)
Launch Jenkins, don't see the projects created in step 3 above.
Investigating...
