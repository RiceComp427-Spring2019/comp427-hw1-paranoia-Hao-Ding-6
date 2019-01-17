# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Hao Ding

_Student NetID_: hd25

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: {Stadium}
- Assumptions:
  - The stadium is located at the center of their city which is densely-populated and has heavy traffic.
  - The stadium is similar to the Rice Stadium and can contain 60000 audiences.
  - There will be a important game bwtween two top ranked team to competefo the title.
  - These two teams have a huge number fo fans and at least 30000 of them will come to the stadium at that day.
- Assets:
  - Audience   
  The first thing I have to think is the safety of such a number of audiences because they are not prepared for any emergency situations while watching and cheering their team. It would be easy for an attacker (such as terrorists, people who support different team, etc) to  inflicts hurt on others during the game. Also, such a number of audiences and crowded environment is the thief's heaven, it's hard to find the thief in that situation without well-designed security measurements. Therefore, the protection on audiences is indispensable.
  - Football team   
  Second, the football teams should also be protected while they are competing at the stadium. There are a lot of cases in the history that terrorists or insane fans rush into the court and attack the players, the consequences range from a false alarm (like a crazy streaker) to the death of players and negative effect on society (such as a terrorist with his gun or bomb). So, it is neccesary to make strict security measurement to protect our players.
  - Public facilities   
  Finally, we should pay our attention to the public facilities like electronic system, seats, guardrail, etc. They are closely related to the safety of audiences and football players because they are used at all times before, during and after the game. If there is something worong with the stadium like power failure, guardrail fracture, etc, there is a strong possibility that the audiences and players would get into a mess and be injured. So we should ensure that the stadium itself is safe.
- Threats:
  - Equipments Damage   
  As we say above, it is very important to maintain the equipments of the stadium since they can directly hurt people if therer is emergency situations like fire, building damaged, etc. Any one from these situations would impose big effect on the people at the stadium, even endanger their lives.
  - Intentional Attack   
  Intentional attack means man-made attack including terrorists, crazy fans, etc. It is unpredictable because you would never know what those people would do in such a feverish, corwded, chaotic atmosphere. Also it is easily to become worse if there is panic-stricken stampede which is likely to happen according to our history.   
- Countermeasures:
  - The first thing we should do is to totally check the status of the stadium including the strength of the buklding and the public facilities before the game. If there is something wrong with the items above, we should fix them immediately. This measurement might cost a lot of money but it is worth it since we can ensure that the safety of all the people at the stadium would not be affected by unexpected damage of the stadium.
  - Then we should deal with the possible man-made issue. We can solve this problem from two angles: First, we should strictly check the identity of the audience while they entering the gate and be sure that they don't carry anything dangerous like knife, bomb, gun, etc. By this we can prevent unauthorized and dangerous people from entering the stadium. Second, we should make sure that nobody can ge to the game field except the football team by adding security staff at the border of game field and short walls to seperate audiences and players. This may require many people and cost a number of money, but it is the most simple way to ensure the safety of players. 

## Problem 2
- Scenario: {Grading}
- Assumptions:
  - Teachers grade the submission using specific system like Canvas.
  - Students also submit their homework via that system.
  - Teachers have the right to change the grade on the system. 
  - Students can only view their submission records and grades on that system.
- Assets:
  - Sunmission material    
  The first thing we should protect must be the submission material such as code, pdf file, txt file and etc. Because teachers have to evaluate the homework according to the submission materials, if they were damaged or lost, there no way for teachers to makr and comment on the assignments.
  - Grade   
  The most important thing for students is the grade, so, after grading the grades must be protected and should not be changed unless it is approved by the teacher. Also the grades should not be lost or stolen because we need them to calculate the final grades and students nedd their grades to adjust their study method. 
  - Submission System   
  Finally, we must ensure that the submission system should be protected and would not be easy to be damaged by someone like hacker. If the system is damaged, we would lost all the data including the submission materials, grades, and the accounts for all teacher and students. It would cost a lot of time to resoter the data or we would never restore the damaged data. Again, the system itelf must be  closely guarded.
- Threats:
  - Unauthorized Operation   
  Unauthorized operation means someone can change the data on the system without regular authorization. For example, a hacker can move around the username-password match and enter the system or just break the password in the database. It is dangerous if that happens because you will not detect the invasion until you search somethign you want and you find it is changed or lost.
  - Teacher Account Revealed
  Also, if the accounts of teacher si revealed, anyone can use the teacher account to enter the system and manage the data on the system. The system would lost its utility in that case because if a student want to get an A+, he/she just use the teacher account the come to the system and change his/her grade in a few seconds. We should not let such things happen.
  - System Crash   
  System crash is a small probability evnet but it is still possible. Just imagine, if the Canvas or Piazza Sytem crashed, we would lost all the data on the system. It would be very inconvenient for teachers to release and grade the homework and for students to submit the homework and view their grades. It cost much to restore the data or build a new system, so we should pay attention to the safety of the system. 
- Countermeasures:
  - First, to ensure that the accounts in the database would not be decoded by someone else, we can update the encryption mode to higher level mode. For example, we can generate a salt for our pasword and store the hash value HASH(key + salt) instead of HASH(key) by which we can improve the safety of our accounts. It might cost time to generate salt but the security of our accounts is ensured.
  - Then we should let the teacher to set some private quesitons like what is the name of your grandfather and at each time they signing in they should first answer the questions and enter system. If someone give awrong answer, the system will record it and check the identity of that one. So even if soneone else get the teacher account, they still can not enter the system. It is a simple way for us to avoid the acount revealing problem.
  - Finally we should maintain the system and backup our data periodically. Because system crach is hard to predict, we will never know when the system would crash. Periodical maintain the sysmtem we can decrease the probability of crashing and data backup can help us to restore the data after crashing. It would cost money to maintain the system and space to backup the data but we cna make sure our system is hard th crash and can restore the data even if it crashed.

## Problem 3
- Scenario: {The security of my computer}
- Assumptions:
  - I have a computer and there is a lot of important and private ducument in it.
  - I should use my username and password to enter my computer.
  - My computer is a MacBook pro with Touch Bar and it is expensive.
  - My computer is easy to be damaged by physical attack.
- Assets:
  - Documents in the Computer
  The first thing I should protect is the ducuments in my computer including my study materials, my vedios, my photos, my games and so on. I have put a lot og things into my computer and used a half of my disk, so if there is something wrong with my ducument, I will lost a lot of treasures and some of them is hard to restore. Also somwone else might be interested in the documents in my computer so it is also possible that my files are stolen by someone else.
  - The Computer Itself
  It is also important to protect my computer itself because if it crashed I would lost my control of the sysmte and can not access the data which is a high road to losing data. Also emergency situation like it fell on the floor and crashed or some water flowed into my computer would wreck it.  
- Threats:
  - Thief
  Because my computer is expensive, it would be noticed by thieves. If I did not pay attention to my computer, it is possible that my computer would be stolen by someone else. In that case I would literally lose my computer with all my data in it.
  - Hacker
  A high-skill hacker can move around my username-password match or just decode my password to invade my system. In that case he can do whatever he wants to do in my computer and would not be detected by me. When I notice that I lost something it is too late to defend the hacking. I should not let that happen.
  - Physical Damage
  Physical damage includes alot of cases like fire, water, dropping, etc. But there is one thing they share in common, if any of them happened, it is a disaster. There might be no chance for you to restoer you data from a physical damaged computer. I believe lots of people destroyed their computer by droppping or water accidently and can do nothign to save it. It is really a disaster. 
- Countermeasures:
  - The first thing I should do is to encode my computer in a high-level way like double check by fingerprint unlocking. Because my computer has a Touch Bar, I can use ti to achive that goal. Even if someone else can break my password, he should also pass the fingerprint check, otherwisehe can not enter my computer. It cost nothing but can improve the safety of my computer.
  - Then I should prevent my computer from any physical damage For example, I can buy a laptop cover to protect it from dropping or hitting. I can but a keyboard membrane to defend the water. 

