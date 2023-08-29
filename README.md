# Data-User-API-Performance-Test

Assignment Summary

This Assignment has automate load test and stress test using Jmeter

Technology used:

.Jmeter


Scenario: 

Find out the actual TPS for if 120000 users can give load for 12 hours
Perform load test on this URL: https://random-data-api.com/api/v2/users

1. You have to find out if the expected TPS (Transaction Per/Second) meet the above requirement.
Breakdown the expected TPS in excel sheet and find out the actual TPS


2. Create another excel sheet where you will try to find out the bottleneck/stress test point. (At which point the system starts to show 1% error)



Load Test :

Here,Expected tps was,120000/43200=2.77777777777777/s
After fining the value , check how system can behave under an expected load.Through gradually increasing time , got a actual tps which is 2.76927549473596/s with 0% error.

![Screenshot 2023-08-30 025711](https://github.com/Sabiya-Sultana/Data-User-API-Performance-Test/assets/134813316/7e35a760-c274-4894-8874-a011532c1665)



Stress Test :

Here, while gradually increase the load then find out bottleneck point.After stress testing got a capacity so far  3.99854452979115/s

![Screenshot 2023-08-30 025851](https://github.com/Sabiya-Sultana/Data-User-API-Performance-Test/assets/134813316/8c1bbe1b-2110-4597-8bd8-4de259157926)





