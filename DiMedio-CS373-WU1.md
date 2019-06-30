Jason DiMedio
CS373
June 30, 2019


##Week 1 Write-Up


This week covered the basics of malware (malicious software), including viruses, trojans, or potentially unwanted programs. This included an introduction to some basic terminology, including white and black, gray (e.g. intentionally installed by a user but still harmful), sample (copy of malware), goat (computer or device sacrificed to testing malware), replication (how the malware spreads) and hash, which is a cryptographically calculated value for the malware.


During the lectures, it was explained that a lot of malware is unoriginal, and kits are often used, including exploit kits, to specify what an otherwise generic piece of malware should do in different cases. On the other hand, sophisticated techniques such as polymorphic viruses are often developed uniquely for a targeted system.


The naming convention for malware was a new concept. Malware names should be a string formatted with Type, Platform, Family, .Variant, and !Information included in that order, separated by predefined punctuation.


External malware services such as virustotal, malwr, Wepanet, Comodo, FileAnalyzer, and DocumentAnalyzer, which scan and analyze files provided to them to give insights into the behavior of the files or whether the files contain malware.


Similarly, native OS applications can be used to observe malware samples. These might include basic searching, accessing the Registry Editor, scheduler, ipconfig and other command line programs, among other examples.


  

![Fig. 1] (WU1-Fig1.png)
*Fig. 1 - Registry Editor, a native Windows application, being used to observe the behavior of a malware sample during a lab session.*


In addition, a lot of anti-malware tools are available, including ProcessExplorer, ProcMon, InstDrv, FlyPaper, AntiSpy, among others.


  

![Fig. 2] (WU1-Fig1.png)
*Fig. 2 - FakeNet, an anti-malware tool, being used to observe the behavior of a malware sample during a lab session.*


Advanced Persistent Threats were also covered. These are threats or attacks perpetrated by advanced attackers who are fluent with intrusion methods and who have a specific objective and are organized and funded. A major example of APTs are governments and organized crime actors, with money being one of the biggest motives.


The goal for these attacks is to get in and out undetected. In one such attack--known as a water hole attack--the attacker first gets into a system and gathers information using, for example, keyloggers or password crackers. This first infected system of an attack is known as "patient zero."


A normal progression for such APT attacks is represented in the "APT-Kill-Chain," which outlines the attacks into stages including reconaissance, weaponization (in which the attacker is building the payload, delivery, exploitation, installation, command and control, and performing the actions and objectives.


Analyzing these threats often comes down to analyzing metadata, which is data indicative of an attack, including the malware itself and other evidence of its behavior. In a dynamic analysis, the malware is observed directly, whereas in static analysis, the malware is examined (e.g. for strings, binary information, and source code). FileInsight is one tool used for static analysis.