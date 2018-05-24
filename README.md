# GiftHub

![Ironhack logo](./public/images/ironhack-logo.png)
## Ironhack Project #2
From March to June 2018 I attended a **Full Stack Web Development Bootcamp** in Paris with [Ironhack](http://www.ironhack.com/en).

The program was very dense yet well structured and I learnt the following tech stack & tools:
- Angular 5
- Node.js
- MongoDB
- Mongoose
- Express.js
- Javascript & Typescript
- HTML 5 / CSS 3
- GitHub
- Bash CLI

GiftHub is the second of three projects I did during the bootcamp. It was created with my fellow Ironhacker @mbbaber, hope you enjoy it!


### [>>Here's the app!](https://ironhack-gifthub.herokuapp.com/)


## Context
The 2nd project happened after five weeks of learning. At this point, we had covered:
- advanced HTML 5 & CSS 3 manipulation
- advanced JS manipulations
- Handlebars
- Heroku app hosting platform
- back-end stack:
  - Node.js 
  - Express.js
  - MongoDB
  - Mongoose

The insctructions were to create an app that would:
- require to create a data model with various Schemas
- allow to signup/login/logout users with various levels of authorizations
- take advantage of the CRUD (Create / Read / Update / Delete) methods over the app's data


## What is the app about?
Making gifts can often be a headache, be it for close relatives or simple acquaintances. Our app aims to ease this process by making it collaborative, so everyone can add their 2 cents and come up with the best gift for everyone.

Basically, the app works around "rooms", or events where you're supposed to bring gifts. People join the room, and have access to two things:
- their own "wall", on which they can present gift ideas they'd like for themselves
- other people's walls, on which they can:
  - see what people proposed for themselves
  - add gift ideas for them (without the person concerned being able to see it)
  - chat with other people about gift ideas
  - upvote gifts ideas. When they do, the list is rearranged to show most upvoted ideas at the top
  - claim a gift, so that everybody knows who buys what
  
  This way, you don't have to come up with gift ideas on your own and can be sure everyone will have the gift that pleases them the most!


## How does the tech work under the hood?
We basically created a set of models that would cross-reference each other to determine who has access to what sections, who sees what and can modify what.

For the "walls", we used two different Handlebars partials to display one's own wall and other regular walls.

All CSS is done by hand.


## Summary
This was the first paired project we had, and with it came a new layer of complexity: working with someone without conflicting with their code and breaking everything!

It also was our first project implying creating and back-end and managing data inside it. Creating the authorizations, the routes, the search mechanisms and display visibility was both a headache and passionating.

Hope you enjoyed using it, and don't hesitate to give me any (constructive) feedback!
