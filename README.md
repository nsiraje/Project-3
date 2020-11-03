# Project-3: WEEK 1

BY: **NAJWA ABDELLA AND SOPHIA BARBA**

#1 **Suspicious Activity**
1. open and read sample_report.txt file
2. Create an empty list to store extracted domains later
3. Use dictionary to print time, activity, and server within a day in ascending order
4. Set variables:
  login_count = 0
  logout_count = 0
  total_count = 0
  suspicious_activity = 0
in order to count number of logins, logouts,total count and suspicious activty count.
5. Use while loop to track the nu ber and time of logins and logouts
   login_count +=1 logout_count +=1
6. If the user logins between 12am-5am or if user logins >5 times in one day,

YES:
  program identifies system as suspicious activity when login and logout count do not match and during 12am-5am
  adds 1 count to suspicious activity: suspicious_activity +=1
  prints time, activity, server, count of logins, logouts, and suspicious activity
  
NO: System does not detect any suspicious activity
**END**


#2 **Irresponsible Activity**
1. open and read txt file
2. Set variables:
  login_count = 0
  logout_count = 0
  total_count = 0
  irresponsible_behavior = 0
3.while loop to track the number of logins and logouts. 
  login_count += 1
  logout_count +=1
4. if logins > more than logouts

YES: irresponsible behavior +=1 a count will be added to irresponsible behavior
    print total number of irresposible behaviors for that day
    
NO: Then the system does not detected equal amount of logins/logouts

**End**

Domain Count

Once the userlog.log file is opened and read, my teammate and I plan to create an empty list to store the domains we want to extract from the users’ emails. We want to read the lines line by line to make sure each one is accounted for. The code we are planning to create will check each line to ensure that the usernames and domain names are separated by the character @. We will use a split() method to make this work. Once they are separated, we record the domain name, track the number of times it occurred, and add them to the empty list. 

System Glitch

Once the userlog.log file is opened and read, we set the 3 separate variables to count the number of logins and logouts as well as the total number of counts. We plan to use a while loop to keep track of the number of logins/logouts and increment by one. More importantly, we will use an if statement to create a condition when the number of logouts is more than logins, there will be two possible outcomes. If the answer to the condition is false, then the system operates as normal. Meanwhile, when the condition is true, then the system identifies a glitch. We will count the number of glitches in a day as 1 count.
