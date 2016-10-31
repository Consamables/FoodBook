# Final project proposal


## The names of everyone in your group
Danny, Philip, Sam


## A general description of your app idea
The Android version of a social networking service that allows people to crowdsource food orders in a particular area.


## A list of features that will be included. Include both:
- required features for an MVP
  - Works for a couple restaurants (stores menu data for these places)
  - Shows pending orders (people want this but no one has committed) and current orders (people have ordered)
  - Displays local restaurants w/ hours and other information
  - Users have three options:
	  - Start an order as an admin
	  - Join a currently admin’d order
	  - Vote for a restaurant not currently being ordered from
- Medium Goals
	- Handle non-menu item data from restaurants (manual addition)
	- Push notifications to let people know food is here
- Stretch goals
	- App published on the Play store
	- Menu in VR
	- GPS data so the admin can track you down and deliver your food


## What technologies/APIs/libraries/hardware-components your app will depend on
- Separate Dropwizard REST API backed by Postgres database
- Local data storage for cache (/redundancy)
- Coarse/fine location data
- Push notifications


## For each team member: three project learning goals. Explain what you hope to get out of the project and how your project will help accomplish that goal
### Danny
- I want to publish this app on the Google Play Store and add tracking of some sort
- Push notifications, I know this requires some sort of service on the backend, and I’m curious how to do it
- I want to make the GPS data tracking screen


### Philip
- Want to learn about push notifications. Both the implementation on the Android side and the needed backend support. If we don’t get to the point of implementing in the app, I want to make my own demo of a push notification and service.
- I want to learn more about GPS location stuff. I’ve used it before, but some of the methods don’t make sense and I want to be able to implement coarse location stuff without too much battery drain.
- Being able to work effectively with Danny and Sam. Three person teams are hard to manage/organize, so being able to stay on task and accomplish more than one stretch goal would be optimal.


### Sam
- Also push notifications.
- Also learn how to use location APIs. Haven’t worked with this yet. 
- Having focused mostly on functionality and not much on UI in the last couple of labs, I’d like to actually get some experience making nice-looking Android layouts.
- Learn how to keep Pip alive for the longest period of time
