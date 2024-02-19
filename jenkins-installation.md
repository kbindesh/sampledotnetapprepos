## Follow below steps to install the Jenkins on Centos 7.9:

    1. sudo yum install java-11-openjdk-devel
    2. java --version
    3. sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
    4. sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key 
    5. sudo yum install jenkins
    6. sudo systemctl start jenkins

## [Install .NET SDK and Runtimes](https://learn.microsoft.com/en-us/dotnet/core/install/linux-centos)
   1. sudo rpm -Uvh https://packages.microsoft.com/config/centos/7/packages-microsoft-prod.rpm
   2. sudo yum install dotnet-sdk-7.0
