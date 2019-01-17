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

_Student name_: Manu Maheshwari

_Student NetID_: mm130

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: Grading
- Assumptions:
  - It was an online quiz.
  - All the results are stored in an online database, hosted on OwlNet.
  - The results of the quiz are published on an online portal, like canvas.
  - A few authorized people have the liberty to change grades. e.g. Instructor and TA's.
  - Instructors are aboveboard and cannot be bribed.
  - The instructor adds the grades onto canvas, and not the TA's.
- Assets:
  - As a instructor I need to preserve the integrity of the grades.
    I wouldn't allow changing of the grades by an unauthorized person. e.g. any student in the class, or a miscreant.
  - As a instructor I need to protect the confidentiality of the grades.
    I need to make sure that a student can only view her grades, and no one else.
  - This point stems from confidentiality, but I need to preserve the 
    privacy of the student grades.
  - The availability of the grades. All students should be able to access their grades in a timely way.
- Threats:
  - An adversary(a student) might try to tamper with the grades, e.g. increase grades to pass the course. (Violating the write property of   grades)
  - A student might release the grades of all the students in the class. (Violating the read property of the grades)
  - A Denial of Serviced attack on the canvas like website would prevent everyone from seeing their grades.
  - Getting an authorized person to change the grades for some incentive.
- Countermeasures:
  - Engineer a more robust website which has better load handling, or even disconnect a client which could be DDosing the server. We could figure out who is DDosing the server using machine learning algorithms. Since we just have to monitor the traffic coming in on the website, it's reasonable.
  - TA's shouldn't be able to change grades without a permission from the Instructor. This feature should be a part of the grading system. The TA's can only alter a grade if the instructor approves the regrade request. (e.g. much like the special registration form for enrolling in select classes which requires instructor permission). This whole request approval system is just a slight addition to the already used software. *OR* We can simply allow the instructor to make regrade requests. This would just require an authentication, very straightforward implementation.

## Problem 2
- Scenario: TSA
- Assumptions:
  - people are going to smuggle all kinds of contraband through the airport e.g. Narcotics, Guns and ammunition, Exotic animals, Explosives, Undeclared goods etc.
  - people hide these things in all kinds of places (e.g. Suitcase walls, stomach, rectal cavity) and in all shapes and sizes.
- Assets:
  - Lives
    - We need to make sure that not a single person on or off flight is harmed by the substance being carried by fellow passengers.
    - If we allow Narcotics, ammunition that could lead to potential health risks for people on the plane and for the people of the country that plane is flying to.
    - Lives of the animals which are being poached for sport and exotic animal products.
    - The lives of the staff that runs the airport, the flights etc.
  - The property of the airport for e.g. the luggage scanners, full-body scanners, monitors, conveyor belts etc.
  - The properties of other passengers is also an asset to be protected
  
- Threats:
  - A person might have ingested insulated balls of narcotics(for the purpose of smuggling) and the person dies creating a mass panic effect.
  - A person hijacks the plane with guns and ammunition.
  - Someone might try to harm the airport property.
  - A suicide somber gets on the plane ...
- Countermeasures:  
  - Sniffing dogs, already a part of the fleet. No added expenditure. This rules out most of the Grade A narcotics and exotic animals.
  - X Ray machines, for things like ammunition and guns. A very standard tool at airports.
  - Random checks on the airports. We need trained staff for this. Staff which can handle full body cavity search and use the latest equipment.
  - More robust background checks on everyone entering the airport, including the airport cleaning, refueling staff.
  - Some better equipment to scan through luggage and better imaging of human body. 3D scan machines have already been rolled out by TSA for both luggage and humans. The cost of these machines is far lesser than the cost of a mis-happening at the airport.
  
  

## Problem 3
- Scenario: We use a small NFC based key chain to get into our Rice Graduate Apartments. There are a few alternative entrances to RGA. The cars enter through a gate, which opens through a sticker on the car. 
- Assumptions:
  - No civilian can enter RGA unless invited by a resident.
  - There aren't rolling gates, if I open the door with my key chain, the person following me can also enter as long as the door doesn't shut. 
- Assets:
  - Security of residents living inside of RGA. We also need to protect their belongings. 
  - Credibility of RGA as a housing project.
  - Property of RGA including club room game, pool table, common television etc.
- Threats:
  - Theft of goods of residents. Some unlawful element(resident or otherwise) may steal from fellow residents at RGA.
  - Vandalism : a resident or any other person might try to harm property of RGA. This costs money to repair and makes the apartment complex look bad.
  - Unwanted civilian entry into the RGA complex using the card sliding door when a car is entering, or tailing a resident and entering into RGA, or stealing a resident's keys.
  - Fire in one of the apartments because of candles, stove etc.
- Countermeasures:
  - Emergency posts for contacting RUPD. Very small installment, space efficient too.
  - Educating the residents about being vigilant for people creating nuisance at RGA. e.g. harming property, smoking in non-smoking areas. This also includes keeping an eye for unknown people entering the RGA complex.
  - Health and safety inspections which check for things like candles, open wires, malfunctioning stoves in apartments. Anything that could cause a potential fire hazard. This needs to be done once a year, so doesn't use a lot of resources.
  - There should be a gate that allows only one person for every key chain scanned. This could rule out the possibility of people tailing residents and entering RGA complex. We could couple this system with an Identity check to make sure no non-resident steals the keys and enters the complex. A simple card reader could be installed, like the one installed at the Library. 
  - Rounds by the RUPD to increase security of the complex.

