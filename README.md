
## Cloud

*The accessibility of servers for storage, compute power, software, etc. over the internet.*
```
Benefit:
        Cheaper/easier to pay to use someone else's servers than to buy, setup, and maintain your own.
Usage:
        Created an AWS S3 bucket for cloud file storage.
```


## DevOps

*A collaborative teamwork style that emphasizes frequent deployment of feature improvements. (Agile development)*
```
Benefit:
        Frequently merging branches into the main branch means that merge conflict are easier to manage.
        More frequent deployments means end users get access to new features/improvements more quickly.
```

## CICD

*Continuous Integration, Continuous Delivery (Deployment)*

*The process of frequently merging changes into the main code branch, and deploying incremental updates/improvements, rather than waiting a long time to merge large changes.*

*Automation is used to test and deploy the app automatically upon merge if all checks pass.*

```
Benefit:
        Automation saves time and eliminates user error at each step in the build/test/deploy process.
```

## Jenkins

*Jenkins is the software that automates the CICD process.*

## Provisioning

*The process of setting up the infrastructure for an app/service. For example, creating VM servers for your app and database, installing required packages, configuring your machines (ports, etc), then starting the servers.*


## Networking

*Method of allowing computers to communicate and send data to each other over the internet (HTTP Requests, SSH, etc)*

```
Usage:
        Created API, connected to it using fetch requests in JS.
        Created VM in Vagrant, SSH'd into it to modify local files.
```

## Principle of Least Privilege

*Users of a system should only be granted privileges they require to do their job.*

*For example, site visitors should not be able view a database.*

*Employees should be able to view the database, but not delete from it.*

*Admins should be the only ones allowed to delete from a database.*

```
Benefit:
        Increases security. Helps prevent data loss/breaches.
```
 
## IAC (Infrastructure as Code):

*The use of configuration files and software such as Terraform, Docker, Jenkins, etc to automate the build/test/deploy process instead of manually performing those steps.*

```
Benefit:
        Easy to version control/share with others, instead of explaining manual steps to reproduce infrastructure.
```

## Packer and Terraform:

*Packer is used to create VM images.*

*Terraform can provision a VM using the image generated from Packer.*