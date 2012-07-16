# Facegroup Timeline Manager
**A facebook timeline with all your groups organized into cool features. Mark a timiline message as "Starred", Tag your groups and view a unique timeline, mark messages to read later, and more.**

## Application
### Front-End

The front-end application will handle the User Interface and communicate trought Socket.IO with the node server.

Instead the Client-side request an new message from a group or multiple-groups, the APPLICATION will PUSH new content to UI, providing less requests and more async communication.

**Users can make thoose commands:**

1. View a full timeline with all groups
2. View a group timeline
3. Set a MESSAGE as a "Star" message
4. Set a MESSAGE as "READ LATER"
5. POST one message into multiple GROUPS
6. Tag GROUPS like "Development", "Church", "Friendship", "Shopping", etc.
7. View a full timeline with tagged groups


### Back-End
The Back-End side will handle all new connections, request data from database and push new content to users. Should provide an API to Front-end side.

** Back-end side must perform some commands: **

1. Request Facebook oAuth Token to register new users
2. Request Facebook Groups from User
3. Request Facebook content from User Group
4. Join group messages from an User into one full Timeline Groups
5. Make cache of groups messages to performance the application


## Wanna help? Fork it!
We need kick-ass javascript programmers to help us.

**See what you can do here:**

1. Server stuff (Node.js Server, NoSQL Database, Background Workers)
2. Back-end stuff (YUI3, NodeJS, NoSQL Database Driver)
3. Front-end stuff (YUI3, Socket.IO, HTML5, CSS3)