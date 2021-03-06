### 2.1.0
* Add AuthorPublishDispatcher component
* Add configuration flag for enabling CRXDE #35
* Add configuration flag for enabling default system users password #36
* Hieradata config file is now generated based on Ansible group vars
* Add configuration flag for enabling package and artifacts deployment on instance initialisation
* Replace Serverspec with InSpec for testing #50
* Remove external package installation during cloud init #43
* Remove unnecessary sleep during cloud init #51
* Add JVM memory opts for AEM Author and Publish #49

### 2.0.0
* Add Stack Provisioner custom hiera configuration support
* TODO

### 1.1.2
* Disable generated system user credentials logging #34

### 1.1.1
* Update aem-aws-stack-provisioner version to 1.1.1

### 1.1.0
* Load Balancers and Auto Scaling Groups can now be created for a variety of network setups. i.e. 1-n Availability Zones, 1-n Subnets
* Change the Publish Auto Scaling Group to use EC2 Health Check Type
* Change the Publish Dispatcher Auto Scaling Group Health Check Grace Period from 15 minutes to 20 minutes
* Enhance the s3_copy_object script to not copy files that do not exist
* Copy content-healthcheck-descriptor from source bucket
* Update aem-orchestrator version to 1.0.0
* Update aem-aws-stack-provisioner version to 1.1.0

### 1.0.0
* Initial version
