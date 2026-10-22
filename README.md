# SonarQube Code Quality Assessment

## Project Overview
This project demonstrates Java code analysis using SonarQube
and SonarScanner on Ubuntu Linux.

## Tools Used
- Ubuntu Linux
- SonarQube Community Build
- SonarScanner CLI
- Java
- Jenkins

## Project Details
- Project Name: Local Sonar Demo
- Project Key: local-sonar-demo
- Source Directory: src
- SonarQube URL: http://localhost:9000

## Tasks Completed
1. Installed SonarQube and verified access.
2. Created a SonarQube project.
3. Installed SonarScanner.
4. Analyzed Java source code.
5. Integrated SonarQube with Jenkins.
6. Reviewed bugs and code smells.
7. Checked the Quality Gate and exported issue data.
8. Prepared project documentation.

## Run Analysis
Configure the SONAR_TOKEN environment variable, then run:

    /opt/sonar-scanner/bin/sonar-scanner \
      -Dsonar.host.url=http://localhost:9000 \
      -Dsonar.token="$SONAR_TOKEN"

## Evidence
Attach screenshots of the SonarQube dashboard, issues,
successful scanner execution, Jenkins pipeline, and Quality Gate.
