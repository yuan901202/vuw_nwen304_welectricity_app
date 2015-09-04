# Welectricity
Welectricity developed by Ninja Hertz

Download App (Android only): https://github.com/yuan901202/welectricity/raw/master/release/welectricity_beta.apk

## Introduction

Welectricity is an educational gaming application designed to teach children aged between 6 to 12 years­old about electricity generation. Its aim is to teach the user how electricity generation is difficult and the effects that this has on the environment. While playing the game the users will have to strike a balance between creating enough energy for their city while keeping pollution to a minimum to stop people moving out of their city. This balance is aimed to show the users that just going all renewable may not be the best bet and vice versa for non renewable. We have chosen the most common power generation plants that New Zealand uses (with the exception of nuclear). All our stats where at first based on actual numbers and then modified slightly to make the game more attractable to our target audience. Because of these reasons the user will be able to gain an understanding about the difficulties in electricity generation and even gain insight into how we may be able to start to tackle this problem.


### Brainstorm Process

This group project is aimed to design and build an innovative and educational application for children. We originally want to design a game application to teach children how to build a water rocket at home, but we need more back-up plans. So I proposed two ideas: First, to build an application called “Electricity Generator” to teach children how to build an electricity generator at home based on Brooklyn Wind Turbine at Wellington, or they can build an electricity generator with apple, lemon or orange. Secondly, to build an application called “Baby Bird” to teach children to learn different birds around the world, but more focus on New Zealand.


### Final Decision

The final design decision is to create an educational gaming application called “Welectricity” (Wellington + Electricity) to let children play with different power plants, which include wind, hydro-power, coal, oil, gas, nuclear and solar power. And then, they can place different power plants on different locations within a map with drag and drop function, and then get the final score which based on following principles: how much power that all this power plants generated, how much money to build all this power plants, and what pollution score with this chosen power plants. Two map views will be available to let the user to play with, one is the main play screen which they can place the power plants on the map in portrait view, another is the city view to show the whole city in landscape view. This educational gaming application target user is 6 to 12 years-old children, total free application with no advertisements and in-app purchases function build in. The reason we decided to design a free, no ads, and no in-app purchases application is because we want to sell this application to power companies or local government. The reason we choose 6 to 12 years-old as our target user is because at this age stage they can complete a task individually, and they can learn to get effort with results. We use ionic and AngularJS framework to handle our front-end client, and use Heroku as our back-end server.


## System Architecture 

To design frontend and backend system, we using authentication to identify the user try to connect to our database server either from our frontend client or outside client. Frontend The frontend uses the ionic framework. This uses angularjs underneath to allow better separation of concerns. With in angularjs we use a few Javascript libraries. Backend The backend server was set up using Heroku and uses a NodeJS with ExpressJS server stack. The database was created in the backend server by using PostgresSQL through the Heroku addon. Three tables were created to deal with different RESTful requests from frontend client. First table is called user data to handle login and registration data. Second table is called gameplay data to handle all data was made during game play in client side. Third table is called power source database to deal with informations that related to all power plants. This three tables were related to each other to handle the data was collected from the client side, and modify it on the server side.


## Contributors

### Engineers:
[1] Tianfu Yuan (me) (https://github.com/yuan901202)

[2] John Armstrong (https://github.com/jman48)

### Designers:
[1] Nicola Roundill (https://github.com/nicolaroundill)

[2] Josh Bottomley-Clapp (https://github.com/joshclapp)

[3] Nicolas Hamilton

