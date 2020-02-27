# DevOps Project 2: Deploy a highly available web application using CloudFormation

The infrastructure is created with a single CloudFormation yaml file called network.yml and a Parameters json file called params.json. There are two utility files to create and update the CloudFormation Stack.  CreateStack.sh and UpdateStack.sh

The network.yml will create the following diagram

## Architecture Diagram

![Diagram](Project%202%20Diagram.png)

 ## Instructions

To create the high availability web server infrastructure use the CreateStack.sh file as shown next:

```
./CreateStack.sh UdacityProject2 network.yaml params.json
```

To update the Stack use UpdateStack.sh 
./UpdateStack.sh UdacityProject2 network.yaml params.json