# Bloom

## Overview

---
A website for burgeoning content creators on websites like Youtube or Twitch looking to grow their channel through networking and a growing fan base.


## User Stories

---
1. The user arrives on the landing page and sees the main headline, with links to login and signup.
2. The user will also notice a list of content creators, with the online/live streamers at the top, while the offline streamers are near the bottom. There is also a link to the given streamers location website.
3. The login/logout tabs take you to their respective areas and the tabs change accordingly to whether or not you are logged in.
4. When a user signs up, they can choose whether they are making a general fan profile, or a content creator profile.
5. When they choose a content creator as their profile type, their profile will have a couple more features, such as creating a community.
6. When the user navigates to the community list, they will see a grand list of communities, with the most "fans" at the top.
7. These community buttons will take the user to that community's page
8. The community pages contain general info about the streamer, where to find them, with links chosen by the creator who made the community.
9. The section also includes a forum area where the creator can sticky posts and fans can post whatever topics they went, with full comment areas for each, however they must be a fan first.
10. The general profile area contains general info, and who that person is a fan of. Creators can also be fans of other creators!
11. Creators have an additional option to post their social media links and make a community.
12. The make-a-community form asks certain questions regarding the type of streaming they do, what they want to name the community, as well as other personalization options.
13. Once all the info is filled out, the streamer will see their community shown off in the community list, and people can start becoming fans!

 


## Wireframes & ERD

---
![ERD](/bloomERD.PNG)

![Wireframe](/bloomhome.PNG)
![Wireframe](/bloomlog.PNG)
![Wireframe](/bloomsignup.PNG)
![Wireframe](/bloomcomlist.PNG)
![Wireframe](/bloomcommunity.PNG)
![Wireframe](/bloomprofile.PNG)





## Routes Inventory

---

| Route       | Description |
| ----------- | ----------- |
| POST /users/signup | add a new user to users table |
| POST /users/login  | send info to back to check password and send user info to the front |
| GET /users/verify | get user info to display profile | 




## MVP Checklist

---
- Login/Logout functionality
    - JWT and hashing
- Nav Bar and page switching/hiding (Routes/Redirects)
- profile creation and types
- community creation and community lists
- CRUD on forum areas
- live interactions on the home page





## Stretch Goals

---
- special creator/admin abilities to delete posts from their own communities
- sticky posts on forum
- fan counts
- filter options on the community list
- liking and becoming a fan interactions
- extra sign-up options in the forms