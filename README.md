# Soul Level Eight

by Giovanni D'Amico

## Summary
---
"Soul Level Eight" is a Streaming Blog for the twitch user "Havoc Zephyr" and the video game he is playing, the 2012 hit release, "Dark Souls". This streaming blog is much more then just a journal of his ventures, It also allows him to show incredible amounts of data to his viewers after he reaches certain checkpoints.

When an entry is pushed by the streamer, users will be able to see his current stats, what armor he is wearing, how many deaths he has, and where he is located in the worlds map. Additionally, players can view interpolated graphs to see the change in frequency of deaths.

The Data is Generated by an executable injector application called [**Cheat Engine**](https://github.com/cheat-engine/cheat-engine/). it is an open source piece of software that will allow the streamer to read and potentially manipulate Memory Address Variables.

Users can comment on each update entry and have conversations about the run.

### MVP:
**Pages**
- **Landing Page/Login**
- **Registration Page**
- **Timeline Page**
  - Each Timeline Element contains a minified banner with streamers current stats.
    - Clicking into the timeline element will display an expanded form of the banner.
    - End Users can comment on this part of the Timeline Entry
- **User Profile Page**
  - basic user display picture, display name, change email, and change password.
- **Timeline Entry Page**
  - this is only visible to the streamer, will take XML data to be processed by the server and converted into a timeline entry.

**End User is able to**: 

view other users comments in timeline, comment on the timeline, expand timeline elements, view full maps with streamers current position and view death graphs.

**Streamer is able to**:

Everything the end user can, but additionally be able to post XML data into forms to create a new timeline entry, delete Timeline Entries, Delete user comments.

**Database contains**

- End User Info
- End User Posts
- Imported Data Blobs
- Timeline Entry Data


### Technologies Used
---
- Flask
- XMLtoDict
- Json
- Flask-SQLAlchemy
- Flask-WTForms
- Flask-Bcrypt
- PIL
- Cheat Engine

- Development DB: Sqlite
- Deployment DB: PostgreSQL

### Future Features
---

Because of the fact that we are using an open source piece of software like Cheat Engine to generate this data, the potential this has rediculous expandibility.

For the sake of this project, Im working with Dark Souls because it has no anti-cheat protection. but there are plenty of other games that this will also work on. additionally:

- CE can be used to send out CMD commands so with some adjustments through LUA, Curl can be used to send requests to the server **automatically.**
- CE can be used to manipulate the game, so viewers can **force events to occur** on the streamers session.

- Commenting can be expanded to allow for markdown so that users can express more in the comments.
- User Display Pictures.
- 

