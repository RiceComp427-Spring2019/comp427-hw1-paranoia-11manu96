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

_Student name_: Dan WALLACH

_Student NetID_: dwallach

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: Grading
- Assumptions:
  - It was an online quiz.
  - All the results are stored in an online databse, hosted on OwlNet.
  - The results of the quizes are published on an online portal, like canvas.
  - A few authorized people have the liberty to chamge grades. e.g. Instructor and TA's.
  - Instructors are aboveboard and cannot be bribed.
- Assets:
  - As a insctructor I need to preserve the integrity of the grades.
    I wouldn't allow changing of the grades by an unauthorized person. e.g. any student in the class, or a miscreant.
  - As a instructor I need to protect the confidentiality of the grades.
    I need to make sure that a student can only view her grades, and no one elses.
  - This point stems from confidentiality, but I need to preserve the 
    privacy of the studen't grades.
  - The availibity of the grads. All students should be able to access their grades in a timely way.
- Threats:
  - An adversary(a student) might try to tamper with the grades, e.g. increase grades to pass the course. (Violating the write property of   grades)
  - A student might release the grades of all the students in the class. (Violating the read property of the grades)
  - A Denial of Serviced attack on the canvas like website would prevent everyone from seeing their grades.
  - Getting an authorized person to change the grades for some incentive.
- Countermeasures:
  - Make a more robust website which has better load handling, or even disconnect a client which could be DDosing the server. We could figure out who is DDosing the server using machine learning algorithms. Since we just have to monitor the traffic coming in on the website, it's reasonable.
  - TA's shouldn't be able to change grades wihtout a persmission from the Instructor. This feature should be a part of the grading system. The TA's can only alter a grade if the instructor approves the regrade request. (e.g. much like the special registration form for enrolling in select classes which requires instructor permission).

## Problem 2
- Scenario: {Stadium|TSA|Documents|Grading|G20}
- Assumptions:
  - explain_your_assumptions
- Assets:
  - explanatory_paragraph
  - explanatory_paragraph ...
- Threats:
  - explanatory_paragraph 
  - explanatory_paragraph ...
- Countermeasures:
  - explanatory_paragraph
  - explanatory_paragraph ...

## Problem 3
- Scenario: Your choice (give a brief explanation)
- Assumptions:
  - explain_your_assumptions
- Assets:
  - explanatory_paragraph
  - explanatory_paragraph ...
- Threats:
  - explanatory_paragraph 
  - explanatory_paragraph ...
- Countermeasures:
  - explanatory_paragraph
  - explanatory_paragraph ...

