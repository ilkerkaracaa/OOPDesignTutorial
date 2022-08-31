# OOPDesignTutorial
## Modeling various problems with Object-Oriented Programming

### Source : https://app.patika.dev/courses/oop
----------------------------------------------------------
## 1) Zoo Management
You design a system to track information about animals in a zoo.

- Animals:
- Horses (horses, zebras, donkeys, etc.),
- Felines (tigers, lions, etc.),
- It is characterized by species in groups such as rodents (rats, beavers, etc.).
- Most of the information stored about animals is the same for all groupings.
species name, weight, age, etc.
- The system should also be able to get the dosage of specific drugs for each animal => getDosage()
- System should be able to calculate Feed times => getFeedSchedule()
The logic for the system to perform these functions will be different for each grouping. For example, the feeding algorithm will be different for horses and different for tigers.

Using the polymorphism model, design a class diagram to handle the situation described above.

![alt text](https://github.com/ilkerkaracaa/OOPDesignTutorial/blob/master/zooManagement.jpg)


## 2) Flight Management System
Design a system for the management of flights and pilots.

- Airlines operate the flights. Every airline has an identity.
- The airline has different types of aircraft.
- Aircraft may be in operation or in a state of repair.
- Each flight has a unique identity, airport to take off and land at, and departure and landing times.
- Every flight has a pilot and co-pilot, and they operate the plane.
- Airports have unique IDs and names.
- Airlines have pilots, and each pilot has a level of experience.
- An aircraft type may need a certain number of pilots.
Draw the Class diagram describing this system.

![alt text](https://github.com/ilkerkaracaa/OOPDesignTutorial/blob/master/flightManagementSystem.jpg)


## 3) Online Movie System
Design the system of the application that sells or rents movies online.

- Movies can be listed and sorted in the app and users can subscribe to the app.
- Users purchase credits through the system for subscription.
- Only subscribed users can rent movies with their credits and the credit value of the rented movie is deducted from their account.
- Regular users and subscribers can purchase movies.
- If the film is not available, it can be requested.
Draw the Class diagram describing this system.
