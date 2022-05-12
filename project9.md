## INSTALL AND CONFIGURE JENKINS SERVER

`sudo apt update`

`sudo apt-get install openjdk-8-jdk`

`wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -`
`sudo sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > \
    /etc/apt/sources.list.d/jenkins.list'`
`sudo apt update`
`sudo apt-get install jenkins`

`sudo systemctl status jenkins`

![STATUS.PNG](./images/JENKINS.STATUS%20.jpg)

`http://<Jenkins-Server-Public-IP-Address-or-Public-DNS-Name>:8080`

![GETTING STARTED.PNG](./images/GETTING%20STARTED.jpg)

`sudo cat /var/lib/jenkins/secrets/initialAdminPassword`

![CUSTOMIZE.PNG](./images/CUSTOMIZE%20JENKINS.jpg)

![READY.PNG](./images/JENKINS%20IS%20READY.jpg)

![WEBHOOK.PNG](./images/WEB%20HOOK%20ADDED.jpg)

![CONFIGURATION.PNG](./images/JENKINS%20CONFIGURATION.jpg)

![BUILD.PNG](./images/BUILD%20.jpg)

![SETTINGUP.PNG](./images/SETTING%20UP%20BUILD%20TRIGGER.jpg)

![TRIGGER.PNG](./images/BUILD%20TRIGGER.jpg)

![ARTIFACTS.PNG](./images/BUILD%20ARTIFACTS.jpg)


![TEST.PNG](./images/TEST%20CONFIGURATION.jpg)

![CONTENT.PNG](./images/CONTENT%20IN%20NFS%20SERVER.jpg)



![NFS.PNG](./images/NFS%20FILE%20TRANSFER%20.jpg)












