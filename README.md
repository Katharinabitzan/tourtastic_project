<<<<<<< HEAD
1.0.3 CSS added
1.0.2 Add ability constraint. Only list members to add to tour if ability high enough.
1.0.1 Add max capacity function. Only allow members to be addd to tour if there is space remaining. <br/>

1.0.0 MVP achieved. Working app. <br/>
0.1.5 List all tours in next 30 days on homepage.  <br/>
0.1.4 Add index and new bookings function. View all bookings. <br/>
0.1.3 List all members booked on a tour in tour.show <br/>
0.1.2 List all tours a member is registered for (tour id) <br/>
0.1.1 Finish RESTful routes for tours <br/>
0.1.0 Finish RESTful routes for members <br/>
0.0.5 Can create, show and view all members <br/>
0.0.4 Create index for members <br/>
0.0.3 Add functions to find tours by members, members by tours, bookings for both. <br/>
0.0.2: Add CRUD (Create, Read: Find-all & Find-by-id, Update, Delete & Delete-all) functions for Tour, Member and Booking classes <br/>
0.0.1: Add Booking class, pass test of existance of variables. <br/>
0.0.0: Add Tour and Member class, pass test for existance of variables. <br/>

# INSTRUCTIONS FOR RUNNING APP


# SCREENSHOTS


# PLANNING


# BRIEF

# Gym

A local gym has asked you to build a piece of software to help them to manage memberships, and register members for classes.

## MVP

- The app should allow the gym to create / edit / delete members
- The app should allow the gym to create / edit / delete classes
- The app should allow the gym to add members to specific classes
- The app should show a list of all upcoming classes
- The app should show all members that are registered for a particular class

### User Stories

#### Manage Membership

_As a gym manager_ <br />
_I want to manage the list of members_<br />
_So that I am storing up-to-date information about members_<br />

**Acceptance Criteria:** Gym managers should be able to create members<br />
**Acceptance Criteria:** Gym managers should be able to edit members<br />


#### Manage Classes

_As a gym manager_<br />
_I want to manage the list of classes_<br />
_So that I have up to date information about what classes are available_<br />

**Acceptance Criteria:** Gym managers should be able to create classes<br />
**Acceptance Criteria:** Gym managers should be able to delete classes<br />

#### Register Users for Classes

_As a gym manager_<br />
_I want to be able to add a user to a class_<br />
_So that I can book their place_<br />

**Acceptance Criteria:** Gym managers should be able to assign members to classes.

#### View all customers assigned to a class

_As a gym manager_<br />
_I want to view all members assigned to a class_<br />
_So that I can see which classes are going to be busy_<br />

**Acceptance Criteria:** Gym managers should be able to view a list of classes, and see the members that will be attending that class.



## Possible Extensions

- Classes could have a maximum capacity, and users can only be added while there is space remaining.
- The gym could be able to give its members Premium or Standard membership. Standard members can only be signed up for classes during off-peak hours.

### User Stories

#### Classes should have a maximum capacity

_As a gym manager_<br />
_I want to be able to assign a maximum capacity to a class_<br />
_So that the class can't be over-booked_<br />

**Acceptance Criteria:** Gym managers should be able to give each class a maximum capacity<br />
**Acceptance Criteria:** Gym managers should not be able to assign members to a class that is already full. (At capacity)

#### Premium Membership

_As a gym manager_<br />
_I want to be able to mark members as having "Premium Membership"_<br />
_So that I can maximise revenue_<br />

**Acceptance Criteria:** Gym managers will be able to assign premium membership to members<br />
**ACceptance Criteria:** Gym managers will be able to assign a time to a class <br />
**Acceptance Criteria:** Gym managers will only be able to assign premium members to classes that take place during peak hours. (7-9am, 5-8pm)


<br />
<br />
**Caution**

You might try to create a Ruby class named `Class` - this is a reserved word in Ruby, so you will have to name your class `GymClass`, or similar.
