# Purpose
query AWS confg data using athena to exatract insightfulll infromation from aws resources configuration state , for this i create this cloudformation template craete all nessasary resources , to be able to query the data after usng only sql query on the optimal way .

![alt text](images/image.png)

# Installation 

After configuring the aws access for the your user , you need to create new cloudformation template using this command :

```bash
aws cloudformation create-stack --stack-name ConfigWithAthena --template-body file://templates/athena.yml