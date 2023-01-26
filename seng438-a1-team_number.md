>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: 15      |
|-----------------|
| Carlos Morera Pinilla                |   
| Toshi Biswas             |   
| Neil Adrian Sarmiento              |   
| Hassan Anwar                |   


**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction

This lab is for interacting and testing out important functionality for the SUT, an ATM simulation. We will use exploratory testing, manual scripted testing and regression testing as well as bug tracking software like Azure DevOps to keep a list of bugs we encounter. Based on lectures, exploratory testing is human-based testing where test cases are created on the fly, basically an "exploration" or a "thinking" activity. Manual functioning testing is the general overview of following a set path of test cases that usually covers functional requirements of the system.

# High-level description of the exploratory testing plan

For the exploratory testing of the ATM simulation, we will target the specific transaction interactions with the actor and the ATM system, these include:
-   Valid, invalid, and negative inputs to the input field of number of 20 dollar bills when we insert the card.(Integers, floats and negative numbers.)
-   Valid (Card # 1 and 2) and invalid input (any other user input) for the card number that are registered on the ATM.
-   Valid and Invalid input for PINS, that is each card registered for each account should only have 1 PIN associated with it. The digit
length does not necessarily matter as long as it is the correct PIN.
-   Testing each transaction option extensively, checking every option to see if for example the amount of money withdraw using option 1, which is $20 does display $20 on the GUI or not, and likewise the receipt log displays the correct amount withdrawn.
-   As well as establishing links to two types of transactions. For example transfering money from a chequing to savings account, and checking to see if the second registered account can access the same cash.
-   Briefly testing the take receipt and balance inquiry features as they are simply just a push of a button to display or delete the text from the receipt text window.

# Comparison of exploratory and manual functional testing

During the exploratory testing phase we found that some benefits of it include a much more broad range of possible testing cases that we can find. That is, with more people executing exploratory tests at will, it is much more likely to find a much broader range of bugs and system defects. At the cost of being much less efficient however as we come up with these tests at random via experimenting with the system.

During the manual functional testing phase, we found it to be much more efficient as all team members follow a set or a subset of test cases, with the initial state of the system and the expected result already recorded, so it is a simple run-and-compare testing. However, due to this limited range of testing, it is much less effective at dectecting a broader range of bugs than exploratory testing, so it is much more likely that some hard-to-find defects can slip under the radar regardless of how many people execute the tests.
# Notes and discussion of the peer reviews of defect reports



# How the pair testing was managed and team work/effort was divided 

Exploratory testing: 
-   All group members participated in pairs, doing an exploratory    session for about 20 mins each pair. The pairs are listed below on Manual Functional Testing.

Manual Functional Testing: Carlos and Neil(50%), Hassan and Toshi(%50)

Regression Testing: 
-   All group members contributed to testing and editing bugs in the new version as well as changing bug reports to the appropritate status after peer review.

# Difficulties encountered, challenges overcome, and lessons learned

Text…

# Comments/feedback on the lab and lab document itself

Text…
