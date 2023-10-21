Jenkins Pipeline for Java based application using Maven, SonarQube, Argo CD, Helm and Kubernetes

![image](https://github.com/rogerbarrow/CI-CD-pipeline-jenkins-Docker/assets/46138186/0183ac53-6a9a-4efd-9197-71fed36bb4cf)

Here are the step-by-step details to set up an end-to-end Jenkins pipeline for a Java application using SonarQube, Argo CD, Helm, and Kubernetes:

Java application 
Jenkins server
Kubernetes cluster
Helm package manager
Argo CD

Steps: 1 - Create a Ec2 Instance because of the size of the application and the tool we are using make sure the Instance t2.meduim or more i will be using t2.large 

![image](https://github.com/rogerbarrow/CI-CD-pipeline-jenkins-Docker/assets/46138186/e2d7dfb5-0590-4873-b496-ddff02e1aab0)

Steps: 2 Is install Jenkins, first get the instance Public IPV4 address
![image](https://github.com/rogerbarrow/CI-CD-pipeline-jenkins-Docker/assets/46138186/84b5a7b1-8705-4050-9a33-7572f93bdbc4)


![image](https://github.com/rogerbarrow/CI-CD-pipeline-jenkins-Docker/assets/46138186/0994aa12-72cc-4427-a7f5-344075a54935)

Steps: 3 SSH into the Instance using the Public IPV4 Adress 
![image](https://github.com/rogerbarrow/CI-CD-pipeline-jenkins-Docker/assets/46138186/923035a4-4e92-4572-8221-597ba556c5ce)

Steps: 4 Create a Jenkins Pipeline 
![image](https://github.com/rogerbarrow/CI-CD-pipeline-jenkins-Docker/assets/46138186/4cfb74c3-a66b-445f-846e-dadf35ff294e)

