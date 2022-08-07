#### Description:
Creating this project will give you the hands-on experience you need to confidently talk about infrastructure as code. We have chosen a realistic scenario where you will deploy a dummy application (a sample JavaScript or HTML file) to the Apache Web Server running on an EC2 instance.

#### Steps:
1. Infrastructure as Code with CloudFormation
2. Networking Infrastructure
3. Servers and Security Groups
4. Storage and Databases

#### Create network resource
```shell
./create.sh myFirstStack network.yml network-parameters.json
```

#### Create instance
```shell
./create.sh mySecStack servers.yml server-parameters.json
```






