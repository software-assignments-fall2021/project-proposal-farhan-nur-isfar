Isfar Oshir, Farhan Mashud, Mohammed Uddin

### Project title
EventEdge

### What and why?

In recent times, event planning can get convoluted and people can get confused as to when is what or what they have to bring. There's been several times when I have tried to plan events with friends, where some may be lost as to what the exact precise details are and there can endless times of tagging people in the group chat. So, this project will incorporate not just messaging but other accessory features as well such as creating the event right then and there in the group chat and the event would be create on Google Calendar. Another feature can be dedicating tasks to certain group mates, so no one has room to mess up.

### For whom?
This software can be used by anyone who wants to plan an event of any kind, such as parties, sporting events, etc. It is basically for friend circles.

### How?

Users will sign up for an account. After logging in, the user can add friends, create group chats, and then start messaging. In addition, there will be options for users to create a google calendar event. The rest in the group chat can either accept or decline the event. If accepted, an event would be added to their Google Calendar through the use of Google Calendar's API. After accepting, our own site will also keep track of the specific user's events in a different page. In the page, each event can have info such as what they have to bring to the event if anything is required to be brought, time, location, etc. 

### Scope

I think it is not too easy because there a lot of relationships to consider when it comes to the managing the database. One component of the project - live updates - is what can be tricky. We need to use Socket.io for messaging, potentially sending/receiving/accepting friend requests, but that can be decided later whether we want the user to just reload the page or if we want to make it live.  I think it is not too ambitious because we are not creating our own calendar system, but we are relying on Google Calendar.
