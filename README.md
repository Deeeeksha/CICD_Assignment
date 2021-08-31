# CICD_Assignment


1. Create a Jenkins pipeline to deploy application present at: https://github.com/knoldus/node-hello
2.  Required command to run the application and the ports being used are present in the Github repository.
3. You are required to use Jenkins Freestyle project to set this pipeline.
4. Requirements:
              a) Jenkins should be set up on a Cloud Virtual Machine and not from the local system
              b) Any commits to the ‘main’ branch should trigger the job on Jenkins and start the build process
              c) Use Poll SCM triggers
              d) The first part of the Jenkins job should be creating the package
              e) The second part of the Jenkins job will be to send the package to another VM and run it there
5. The validations can be performed by hitting endpoints: <VM_IP>:3000 or <VM_IP>:3001

