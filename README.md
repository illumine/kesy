# KESY project
Free Software for Student Evaluation.

## What is what

clevercloud: deployment descriptor for CleverCloud provider.

mysql: the  MySQL workbench for the schema. Use this to create the backend - MySQL database.
and the JPA DAOs using Hybernet, Ibis or default JPA that does reverse engineering the DB.

src: ZUL, Java and deployment descriptors files for the prototype

pox.xml: Maven build file. Deploys to JeTTY

build.xml: classic Ant build file. Creates the ZKTest.war deployment file.

Both working fine within IDEA but also outside. No dependencies from IDE.

zklibs: the ZK platform library JAR files. Needed for Ant build.



## Dev deployments at Clever-Cloud
Deployed at:\
https://console.clever-cloud.com/users/me

Read:\
https://www.clever-cloud.com/doc/clever-cloud-overview/add-application/ \
https://www.clever-cloud.com/doc/java/java-maven/   \



### ZK Resources
ZK Deployment Manually - How to create a ZK WAR -  Must Read\
https://www.zkoss.org/wiki/ZK_Installation_Guide/Quick_Start/Create_and_Run_Your_First_ZK_Application_Manually

Tutorial for installing and testing ZK with IDEA -  Must Read\
https://www.zkoss.org/wiki/ZK_Installation_Guide/Quick_Start/Create_and_Run_Your_First_ZK_Application_with_IntelliJ_and_ZKIdea