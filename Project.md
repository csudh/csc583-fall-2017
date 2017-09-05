# Course Project

## Background

This semester we have been tasked by a customer to build a social networking bulletin board system.  

## Functionality

While the customer does not have specific software requirements, the customer has a certain expectations of what the system is suppose to do:

- User registration
- Registered users can invite friends
- Registered user can create board message
- Board messages can have discussion
- System must have metrics on user behavior but does not attribute on specific user

## System Requirements

The customer does not have a specific requirements on how the system is to be built.  However, it's rather clear that at the minimum, we should incorporate the following into our design and implementation:

- Frontend web application that is based on the SPA design
- We must expose the internals of system with an RESTful API
- Scalable backend storage layer for persistent data warehousing

## Constraints

Because our customer expects a closed system, the following constraints required: 

- Board messages are only visible by friends, or friends of friends, etc.
- Association (friendship) is by established by invite or request
- A user can only know his or her friends (bi-directional knowledge) but does not know his or her friends' friends

## Teams

In an ideal software development environment, a software project would consist of teams that are responsible for these tasks:

- Requirements
- Architecture
- Frontend
- Backend
- API
- DevOps
- Testing and Validation

For our class, we will have a similar team structure.  The only difference is that we will designate a team-in-charge for each of the above tasks.  The team-in-charge is responsible for the delivery of documentation for the assigned task and ensuring that coding is completed.  Coding is to be accomplished by the entire class.

## Deliverables

Everyone in the class will be go through the development of the entire system.  One of the grading criteria is based on the LOC or line of code contributed via Git Pull requests.

Ultimately the final product for the course is a completely working product.  We recognize that while there might be unfinished components, the system must work.  Consider the immortal words of Gene Kranz on the Apollo 13 mission:

> Failure is not an option.
