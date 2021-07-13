# Background
The goal of this document is to help with the basics of installing Fedora and the needed artifacts 
on Fedora. Many resources have followed this and expressed the happiness in the performance of Fedora.

# Base Platform Install
The following are the implementation steps:

1.  Download the current release (get the X86_64) https://getfedora.org/en/workstation/download/
2.  Setup the machine in your local virtual management tool - Parallels, VMWare, VirtualBox, HyperV, etc. - Personal recommendation is at least 4 vcores and 12GB RAM and at least 64GB space (the drive space does not need to all be allocated immediately).
3.  I would recommend that you implement directories outside of the /home directory to not run into substantial potential space issues with /home and so forth.
    What we have built out is:
    /Development
    /OpenSourceTech
    /RedHatTech
    Here is a general link for knowledge: https://averagelinuxuser.com/linux-root-folders-explained/ <br/>
    Here are some generic instructions we have for creating /Development
    ```sudo mkdir /Development```
    Changing ownership and groups examples https://www.thegeekstuff.com/2012/06/chown-examples/

## Add-Ons to Base Platform
One you install the base platform there are several add-ons that are needed to be installed.

1.  Install GIT
    ```sudo dnf install git``` <br/>
2.  Needed Installs: Java
JDK 1.8 - ```sudo dnf install java-1.8.0-openjdk``` <br/>
JDK 11 - ```sudo dnf install java-11-openjdk``` or ```sudo yum install java-11-openjdk-devel``` <br/>
When switching between JDKs use ```sudo alternatives --config java```. This way you can select the JDK for your needs 
    and then run java -version to check this change has happened.
3.  Maven 
```sudo dnf install maven``` <br/>
4. Kafka
   https://kafka.apache.org/quickstart   
5. RDBMS - Relational Databases
MySQL (Using MariaDB): https://fedoraproject.org/wiki/MariaDB <br/>
   ```sudo dnf install mariadb``` <br/>
Postgres https://fedoraproject.org/wiki/PostgreSQL
   ```sudo dnf install postgresql```<br/>
6. RDBMS IDEs - there are a lot, commonly used is Dbeaver (they have a purchased and community). https://dbeaver.com/download/lite/
7. Development Tool/IDE/Text Editor
We personally see a lot of folks using IntelliJ and its has a ton of ! https://www.jetbrains.com/toolbox-app/ is a tool you can download and install and it can help you access Community or Purchased subscriptions.

# Cloning Code and Getting Running
One you install the base platform there are several add-ons that are needed to be installed.

You can now start going and cloning repositories
https://github.com/RedHat-Healthcare/DataSynthesis.git
https://github.com/RedHat-Healthcare/iDaaS-Simulators.git
https://github.com/RedHat-Healthcare/iDaaS-Connect.git
https://github.com/RedHat-Healthcare/iDaaS-Route.git
https://github.com/RedHat-Healthcare/iDaaS-KIC.git
