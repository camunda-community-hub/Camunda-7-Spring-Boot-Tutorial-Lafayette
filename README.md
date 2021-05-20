# Camunda Spring Boot Tutorial Lafayette
This project is used as part of a video tutorial in order to show how you can use various features of Camunda in a spring boot application

## What is this all about?
When creating example projects I like to ensure that the examples I use are as close to real world use cases as possible and so in this example we'll be building a process in which we can help one of my favourite historical figures [Gilbert du Motier, Marquis de Lafayette](https://en.wikipedia.org/wiki/Gilbert_du_Motier,_Marquis_de_Lafayette) to do what he does best - get involved in revolutions! 

This is broken up into 4 parts and in the end we're looking a process that will help Lafayette with a more efficient way to ruin things for the French and British monarchy. 

![process](./src/main/resources/images/laffProcessDiagram.png)

## What will you learn?
* How to setup a spring boot project with Camunda
* Understanding the components of the project
* How to create forms and link them to user tasks
* How to write java classes that can be run by Service Tasks
* How to configure an XOR gateway based on process data
* How to configure non-interrupting timer events
* How to trigger and catch BPMN errors thrown from Java Code


### Part One: Lafayette's Departure 
<span style="color:Orange">Using User tasks and Camunda Forms</span>.
![LafayetteV1](./src/main/resources/images/LafayetteV1.png)


### Part Two: Lafayette Crosses the Ocean 
<span style="color:Orange">Using Service Tasks, Java Classes and Gateways</span>.
![LafayetteV2](./src/main/resources/images/LafayetteV2.png)


## Part Three: Lafayette Writes Home
<span style="color:Orange">Using Timers and User Tasks</span>.
![LafayetteV3](./src/main/resources/images/LafayetteV3.png)

## Part Four: Disaster at Sea for Lafayette
<span style="color:Orange">Using Java to throw BPMN Error Events</span>.
![LafayetteV4](./src/main/resources/images/LafayetteV4.png)