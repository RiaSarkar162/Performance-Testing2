# Performance-Testing on E Commerce Website

Tested website name: La Mode(E-Commerce)

I’ve completed performance test on ❖frequently used API for La Mode website. 
❖ Run in non-GUI mode.
❖ Test Report Generate on HTML. 
 

5 HTTP Request has been used.Those are:

❖https://lamodebd.com/

 ❖https://lamodebd.com/collections/monsoon-collection-1
 
 ❖https://lamodebd.com/pages/aboutus
 
❖https://lamodebd.com/pages/contact-us
 
 ❖https://lamodebd.com/pages/store-location-2
 
❖https://lamodebd.com/blogs/news

 ###  Scenario 1.
 ❖5 users click on the site at the same time

❖Ramp-up period 10 seconds.

❖Loop Count 1

5 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 8 And Total Concurrent API requested:575.
While executed 5 concurrent request, found 2 request got connection timeout and error rate is 0.35%. 




 ### Total Transactions Per Second

 ![jmeter 1](https://user-images.githubusercontent.com/68694418/194819806-c7c1c14b-a4b4-4957-8e7e-08c0abedffbb.png)
 
 The Avg number for Total Transactions Per Second 8 transactions/per second.
 
  ###  Scenario 2.
 ❖10 users click on the site at the same time

❖Ramp-up period 10 seconds.

❖Loop Count 1

10 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 7.5 And Total Concurrent API requested:1150.
While executed 10 concurrent request, found 10 request got connection timeout and error rate is 0.87%. 

 
