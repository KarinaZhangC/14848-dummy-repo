# 14848-dummy-repo
Teammate: Giselle (Caiyi) Deng, Andrew ID: caiyid </br>
This is a dummy repository for 14848 Cloud Project. It contains a simple python program (hello.py) and Sonar-project.properties file. </br>
It will be scanned during a Jenkins Pipeline job and the scanning result will be shown on SonarQube. </br>

References:
- projectKey in Sonar-project.properties: https://docs.sonarsource.com/sonarqube/9.8/analyzing-source-code/scanners/sonarscanner/
- Sonar-project.properties to solve “not authorized” error: https://community.sonarsource.com/t/error-youre-not-authorized-to-run-analysis-please-contact-the-project-administrator/11979
- sonar.login and sonar.password and their values in sonar-project.properties: 
  - https://sonar-jenkins.blogspot.com/2013/06/please-provide-values-of-properties.html
  - https://github.com/jhipster/generator-jhipster/issues/20773
- Default SonarQube username and password: https://docs.sonarsource.com/sonarqube/latest/instance-administration/security/
- Medium.com for Sonar-project.properties location (put it in dummy repo) and setting up Jenkins Pipeline: https://medium.com/@rosaniline/setup-sonarqube-with-jenkins-declarative-pipeline-75bccdc9075f
