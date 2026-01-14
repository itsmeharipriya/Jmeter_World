# Jmeter_World
# JMeter Performance Testing Portfolio

## Project Overview
This project demonstrates real-time performance testing scenarios
using Apache JMeter on REST APIs and database layers.

## Tools & Technologies
- Apache JMeter 5.6.3
- JDBC Connection Configuration
- REST APIs
- CSV Data Set Config
- Non-GUI Mode
- HTML Dashboard Reports

## Test Scenarios Implemented
- API testing with GET & POST requests
- Token-based authentication (API)
- JDBC validation of backend data
- Controllers (Loop, If, Transaction)
- Timers to simulate real user pacing
- Recording using HTTP(S) Test Script Recorder
- Command-line execution
- Result analysis using JTL & HTML reports

## Execution
Command used:
jmeter -n -t commandLine.jmx -l result.jtl -e -o HTMLReport

## Reports
- JTL file for raw results
- HTML dashboard for analysis

## Key Learnings
- Identified bottlenecks using response time & throughput
- Understood impact of timers on load
- Validated API responses with DB data
