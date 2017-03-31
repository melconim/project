# CSCI 2254 Web App Development

## Course Project

#### (30 Points) Due via GitHub push: Wednesday April 3, 11:59PM.

---

This is a 3-person final project. If you don't know anyone in the class, you can use the Piazza partner finding tool to find partners, or you can ask a staffer for help. The course project involves designing and developing a web app. When implemented, the app should be deployed on the cslab1.bc.edu server.

#### Logistics

1. Send an email to the entire course staff identifying

   1. The full names of all three team members,
   2. A name for your team,
   3. A short (one or two paragraph) summary of the app.

   The course staff will

   1. review the proposed web app and give you feedback;
   2. create a GitHub Team providing shared access to GitHub repositories for all team members. Course staff will arrange for the repo of the alphabetically first team member to be shared by the entire team. For example, if the team members are Andrews, Keene & Muller, then the GitHub repository named `project-Andrews` would be shared among the team members and the course staff. If you would like additional shared repos, just let us know.
   3. assign your team a dedicated port number for use on the cslab1.bc.edu server.

2. When the app is working, you should clone the repo to an account on cslab1.bc.edu. When you run the app make sure that it is listening on your designated port number.

#### App Requirements

The requirements for the app are 

1. That it be of your team's own design and implementation
2. That it implements a server using Node.js that interacts with at least one client.

Your app should be well designed with modular JS. It does not have to use React or any other specific framework, library, database or Web APIs. Though we highly recommend using Express.js. Think carefully about how to split up the work. It usually makes sense to have a front-end person who is responsible for the UI, it might make sense to have a back-end person who is responsible for the server-side logic.

#### App Ideas

You're encouraged to come up with your own idea for the project. If you don't have anything in mind, here are a few.

**Words with Friends** Make a simple version of the popular game, words with friends. The app would allow some number of parties to log in and start a game. The server manages the game rendering the board to all players and accepting their moves in turn.

**Best of BC** This is an app used in previous semesters. The app allows multiple users to develop and share a database of points of interest on the BC campus. The app uses the google map API to display the points on a map of the BC campus. The display of the points should record the longitude and latitude of the point together with a short description of the point explaining what is to be found there.

For other ideas, feel free to talk to the intstructor.