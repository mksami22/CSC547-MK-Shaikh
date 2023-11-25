# CSC547-MK-Shaikh

This repository is built as a part of the CSC547-Cloud Computing Project. The repository contains all the YAML files, locust server file and the project report. 

Here are the configurations we have used to test with Locust:
- Number of users during peak concurrency - 40
- Spawn rate - 0.5
- Total number of requests - 63522
- Requests per second - 793.17
- Failures per second - 0.01   


Steps to run tests using Locust:
- Run the locust.py file which runs the Locust server.
- Initialize the values for peak concurrency and spawn rate and provide the link to the target host.
- Run the test
