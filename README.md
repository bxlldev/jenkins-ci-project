# Prerequisites
#
- JDK 11 
- Maven 3

# Jenkins Plugins
- Nexus
=> Nexus Artifact UploaderVersion 2.14
- SonarQube
=> SonarQube ScannerVersion 2.17.1
- Git
=> Installed by default
- Pipeline Maven Integration Plugin
=> Pipeline Maven IntegrationVersion 1368.vfb_8509d7b_869
=> Pipeline Utility StepsVersion 2.16.0
- BuildTimestamp 
=> Build TimestampVersion 1.0.3

# Techstacks
![image](https://github.com/bxlldev/jenkins-ci-project/assets/127035655/6a9253c1-22ef-4495-88b0-360f7feb900b)

- Jenkins => created by EC2 for pipelining (Prerequieste JDK & Maven)
- Git/GitHub => for fletch code
- Maven => for build artifacts & unit test
- SonarQube => for code analysis (check whether vulnerability & code quality & generate report & send the result to SonarQube Server with Quality Gate conditions)
- Sonatype Nexus Repository  => created by EC2 for versioning and uploading artifact once pass code analysis.
  


