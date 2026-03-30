JMeter Load Testing 

Overview

This project contains the Apache JMeter test plan created for performing load testing on the application.

Name: LA-Metro
Test Type: Load Testing / Performance testing


Objective: Validate system performance under expected user load and Ensure system stability under concurrent users

Test Scenarios: Login API Load Test

Test Configuration:

Number of Users (Threads):10
Ramp-Up Period:20
Loop Count / Duration:1
Protocol: HTTP / HTTPS

Environment Details:
Environment: Dev Env.

Base URL: http://65.0.163.250/incident-response-time

Project Structure
LoadTestingReport.jmx/
 ├── test_plan.jmx
 ├── data/
 │    ├── Http Request
 │    └── Assertion
 ├── reports/
 

How to Run the Test: 
Open Apache JMeter
Click File → Open
Select LoadTestingReport.jmx
Configure threads if needed
Click Run (▶)

Reports & Results:
Results can be generated using:
View result in tree
view result in table
graph report
Summary Report
Aggregate Report

Feedback Required:

Please review and provide feedback on:

Test coverage
Load configuration
validations
Performance improvements

Prepared By: Priya Kumari
