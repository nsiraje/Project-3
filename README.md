# Project-3: WEEK 1

BY: **NAJWA ABDELLA AND SOPHIA BARBA**

Domain Count

Once the userlog.log file is opened and read, my teammate and I plan to create an empty list to store the domains we want to extract from the users’ emails. We want to read the lines line by line to make sure each one is accounted for. The code we are planning to create will check each line to ensure that the usernames and domain names are separated by the character @. We will use a split() method to make this work. Once they are separated, we record the domain name, track the number of times it occurred, and add them to the empty list. 

System Glitch

Once the userlog.log file is opened and read, we set the 3 separate variables to count the number of logins and logouts as well as the total number of counts. We plan to use a while loop to keep track of the number of logins/logouts and increment by one. More importantly, we will use an if statement to create a condition when the number of logouts is more than logins, there will be two possible outcomes. If the answer to the condition is false, then the system operates as normal. Meanwhile, when the condition is true, then the system identifies a glitch. We will count the number of glitches in a day as 1 count.
