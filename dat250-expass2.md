## Experiment 1

**Assignment 4.3 - 4.5** 

I had a lot of problems during this part of the project and found the tutorial confusing and not precise enough, especially when using a Mac. After the installation of derby I continued with the tutorial on step 4.3 and got a "JDK unsupported" issue when I tried to run Main. I initially thought it was because java 16 was too new, so therefore I downloaded java 12 but that did not help. I tried to fix it for 5-6 hours and eventually made more problems then I had and couldnt even run the program. I am not used to working with IntelliJ and ended up installing eclipse as well to see if I could run the program from there.(I could not). I also ended up uninstalling derby, maven and more to see if I did something wrong along the way. I eventually fixed the problems by opening the pom.xml file and installing the required dependencies. I then changed the java version to 12 again, but forgot to change the run configurations the first time around. 

I tried to install lombok but as i found that tutorial difficult for mac users as well, and i had already used a lot of time on the first part i decided not to spend more time on it. 

<img width="1345" alt="Skjermbilde 2021-09-09 kl  18 06 24" src="https://user-images.githubusercontent.com/42602722/133216374-fd266009-3850-4c4d-bd0f-dbea8c48a4b0.png">

<img width="1072" alt="Skjermbilde 2021-09-12 kl  16 00 39" src="https://user-images.githubusercontent.com/42602722/133216727-ff53dfd5-5a6e-4235-a10c-862621f18a78.png">


**Assignment 4.6**

I followed the tutorial but misunderstood at some point when the tutorial tells you to make it a new java project. I should have made it a maven project. The code should be fine but i did not delete the project and make a new maven project, so i could not run the JUnit test. 



## Experiment 2

I found this part easier to make, but got a "No Persistence provider for Entity Manager named..."  error when running. After some research i found out that it could be that it is not looking in the right place for the META_INF folder. I noticed that i forgot to make a META-INF folder under the resources directory, I tried to add it but just ended up with another persistence exception. I already used a lot of time trying to fix the errors in experiment 1, and at this point I was already on overtime, so I didnt get a chance to try to fix it any further. 

<img width="893" alt="Skjermbilde 2021-09-13 kl  22 31 11" src="https://user-images.githubusercontent.com/42602722/133216935-4c09d6f8-f03a-4af7-a81b-13c156016c22.png">



## Final notes

I found the tutorial difficult to follow. Very many technical issues along the way made this assignment very frustrating, because of this i spent more time trying to solve them and had a short amount of time on solving the actual exercise. Additionally I had trouble opening IntelliJ for 24h which also delayed my work a lot. 

<img width="285" alt="Skjermbilde 2021-09-13 kl  14 10 45" src="https://user-images.githubusercontent.com/42602722/133217459-60d3687c-074e-40a0-a5e4-add953acab18.png">

code: 
https://github.com/julieheldal/Dat250-Assignment2
