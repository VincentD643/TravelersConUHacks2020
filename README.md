## Inspiration
At first, we wanted to build a messaging app. So, we asked ourselves how can we attract users to use the application since there's so many messaging app out there. Then, we we're talking about traveling solo abroad and we realized that it's kind of difficult to meet new people to hang out with when you're shy. This is how we came up with this idea.

## What it does
Travelers is a small social network for travelers wanting to meet with other travelers. After signing-in a list of people that are nearby is made available with the possibility to chat with them. The users location will eventually be changed to a heatmap / radius for privacy purpose. 

## How we built it
We built this project as a team of 4. We decided to split the team with 2 team members working on the backend using Nodejs and 2 team members on the frontend using Vue.js. Although we separated the responsabilities, everyone ended up working on everything. For the backend, we created an api with Nodejs and MongoDB, then we implemented Socket.io for our real time chat. Vue was a bit of a learning curve for two members of our team, but we still managed to pull it off.

## Challenges I ran into
One of our biggest challenge was implementing the real time chat with Socket.io. Since we were saving every messages in our database, we needed to build a system that was efficient and would not be overloaded by the number of messages received at the same time. 

## Accomplishments that I'm proud of
This was our first hackathon, nobody expected anything from this. We just wanted this to be a learning experience by getting out of our comfort zone. We also wanted to create a project to add content to our Github as many of us were looking an internship in software development. 

We're also very proud that we were able to work together as a team to accomplish this project after working on it for many hours without breaks. 

## What we learned
We learned a lot of things about sockets and mostly Socket.io. We also improved our skill in web development. 
However, the most important thing we learned is how to work as a team. We needed to communicate clearly and work efficiently. I believe we were able to do that. 

## What's next for Travelers
After the hackathon, we want to refactor our code in order to use the best practices. Since we had less than 24 hours to build this, we did not have much time to do a lot of code reviews. We also want to improve our usage of the map since we want to improve the privacy of our users.
