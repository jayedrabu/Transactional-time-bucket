# Transactional-time-bucket
This project is about detecting ATM users transactions timing pattern. I have used a dummy csv file containing transactional details of various users. The program would divide the timing into four time buckets, namely; frequent transaction timing, moderate transaction timing, least transaction timing and non-transactional timing. Once the system gathers enough transactional timing from a user, next time when the user swipes his card, the system will determine what transactional time bucket does the present transaction falls in. 
The timings mentioned in the screenshots are in 24 hrs format. 

For example: 
For account number ‘12345’,
Frequent transactional timing: 5PM-6PM (17 represents 5 in 24 hrs time format)
Moderate transactional timings: 9-10 AM
Least transactional timings: 1-2 PM, 2-3 PM
Non-transactional timings: 12-1 AM, 1-2 AM, 2-3 AM, 3-4 AM…

In graphical representation, 
Blue dot represents Frequent timings,
Red dot represents Moderate timings,
Light green dot represents Least transactional timings.
