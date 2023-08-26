# Load_Stress_Performance_Testing_Jmeter

Dear viewers, 

I’ve completed performance test on frequently used API for test App. 
Test executed for the below mentioned scenario in server 000.000.000.00. 

300 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 30 And Total Concurrent API requested: 1800 Error Rate  0%.

500 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 50  And Total Concurrent API requested: 3000 Error Rate  0%.

1000 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 100 And Total Concurrent API requested: 6000 Error Rate  0% .

1200 current Request with 1 Loop Count; Avg TPS for Total Samples is ~ 102 And Total Concurrent API requested: 7200 Error Rate  0%.

1300 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 107 And Total Concurrent API requested: 7800 Error Rate  0.58% .

1500 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 92 And Total Concurrent API requested: 9000 Error Rate  4.64% .

While executed 1300 concurrent request, found  45 request got connection timeout and error rate is 0.58%. 

Summary: Server can handle almost concurrent 1250 API call with almost zero (0) error rate.

Reports:

<img width="364" alt="image" src="https://github.com/rifat12927/Load_Stress_Performance_Testing_Jmeter/assets/66294509/6236028b-356e-4a09-8db3-873c9c6bf08a">
<img width="739" alt="image" src="https://github.com/rifat12927/Load_Stress_Performance_Testing_Jmeter/assets/66294509/561dfc2e-0f4b-4b86-b260-7b7418502f51">

