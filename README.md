# QA_Group_Project

Server Ports:
---------------------

Gateway: 8081

Getters: 8082

Verification: 8083

GroupBooking: 8084

JMS ActiveMQ: 8161

React: 3000

Some details
----------------------

Scrum Master - Joe Simmons

QA - Rana Mittra

3 Devs (Tech lead/researcher)

Senior dev JH

1400-1530 Jordan time. Wk 1.

Can't merge to master w/o JH approval.
Don't do massive merges.

Presentation last day.

5 members
1 scrum master (SM)
-should know whats going on and will be asked by staff how the group is doing

1 Quality Assurance (QA)
- check the code is not a pile of crap
- role is to be a quality gate before it gets checked by Jordan
-70% code coverage (unit tests)
- 0% code smells, sonar cube
- have an eye for detail
- gotta have an eye for detail
- cant be same person as SM
- check variable names, encapsulation, package structure, hardcoded strings

3 Normal devs ( plebians)
-suggest to have a technical lead doing research if new technology is used



Jordan Harrisson is going to sit in on the scrums


10-11:30 Jordan will be the senior developer for team 1
11:30-13:00 Jordan will be with team 2 
14:00-15:30 Jordan will be with team 3
15:30-17:00 Jordan will be with team 4


1 Git Repository
Feature branch model, 
Jordan must OK a push to the Master branch , the master branch must remain untouched
can only merge to master within your groups alotted time with Jordan harrison 
dont merge 100000000 lines of java code at one time



Project is 2 weeks long, 2 sprints

Presentation for deliverable


archetecture requirements

Front end - Could be built in react, but up to us if we want to use anything else
Front end is going to communicate with our "Gateway API" (gateway api is like our account api)

project must have at least 2 Microservices, they can be quite complex or quite simple
CRUD Application, must persist data 
Retriever interacts with Database
Must use a database, if the data is structured use SQL otherwise use Mongo
if user doesnt need a response, use a queue (fire and forget) if your user needs feedback dont use a queue for adding objects to DB

DockerCompose devops
utilize jenkins
