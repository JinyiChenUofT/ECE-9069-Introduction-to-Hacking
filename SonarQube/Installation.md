Installation and Setup
======================

Go to [SonarQube Downloads](https://www.sonarqube.org/downloads/) and downloads the free Community version

![SonarQube Download Page](./images/SonarQubeInstall1.png)


### Windows

Select your operating system folder under /bin folder, and execute "StartSonar"

Open a new broswer and go to http://localhost:9000/, type user "admin", password "admin" to login in for the first time and update your password for later usage. Then you have seen the user interface of SonarQube.

In order to scan your project, go to [SonarScanner Downloads](https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/) and downloads sonar-scanner.

![SonarScanner Download Page](./images/SonarQubeInstall2.png)

Open System Properties - Environment Varaibles - Path, add the location of SonarScanner's bin folder to the path.
For Example: C:\sonar-scanner-cli-4.6.2.2472-windows\sonar-scanner-4.6.2.2472-windows\bin

Open a Command Prompt, type "sonar-scanner" to verify the settings.
 
In http://localhost:9000/, create a project manually.

![SonarScanner Home Page](./images/SonarQubeInstall3.png)

Input your project name.

![SonarScanner Create Project Page](./images/SonarQubeInstall4.png)

Select "Locally" to analyze a local project.

![SonarScanner Create Project Page](./images/SonarQubeInstall5.png)

Create a token using a specific name.

![SonarScanner Create Project Page](./images/SonarQubeInstall6.png)

Select the option and the OS for your project. Then you will have a command you could copy to execute the scanner.

![SonarScanner Create Project Page](./images/SonarQubeInstall7.png)

Excute the command in your project folder and then the scan result will be displayed in the user interface.

![SonarScanner Project Page](./images/SonarQubeInstall8.png)


#### Mac

Start the SonarQube with ./sonar.sh start

![SonarScanner Home Page](./images/start.png)

In http://localhost:9000/, create a project manually.

![SonarScanner Home Page](./images/SonarQubeInstall3.png)

Select the option and the OS for your project. Then you will have a command you could copy to execute the scanner.

![SonarScanner Create Project Page](./images/1646427955(1).png)

Download the sonar-scanner by using the "brew install" command line, and check the version.

![SonarScanner Create Project Page](./images/installScanner.png)

The scan result will be displayed in the user interface.

![SonarScanner Project Page](./images/homepage.jpg)
