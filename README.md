

# Event platfrom -  Security Model in ActionGUI
## Entity Permissions

### Core Information
- [x] Users (i.e., anyone who is logged in) can create public events.
- [x] Everyone (i.e., also users who are not logged in) can read a public event’s core information (title, description, location, date, owner) and any event’s categories
- [x] For private events, only its attendants and users invited to the event can read that information.
- [x]  Only managers of an event can edit the core information with the exception of the owner who cannot be changed but only set initially

### Attendants
- [ ] For public events, users can see who is attending them and who is managing them.
- [ ] For private events, only attendants and those who have an invitation pending can read that information.
- [ ] Only the owner can promote attendants to managers and demote managers to attendants.
- [ ] Managers can remove attendants from the event, but only if the attendant is not a manager.
- [ ] They also can add those who requested to join an event as attendants.
- [ ] Everyone besides the owner can remove themselves from attending the event.
- [ ] Everyone can add themselves as attendant to a public event, if they have been invited.

### Invitations & Requests
- [ ] Everyone can request to join a public event and
cancel their requests.
- [ ] Only event managers can invite users to events they manage, cancel invitations, and accept and deny request.
- [ ] An invited user can accept or decline the invitation (in both cases, the invitation is deleted). Managers can see all invitations and requests for the respective event.
- [ ] Invitations are read-only, i.e., once they have been assigned, the values of invitee, invitedBy, and event cannot be changed.

### Message Board
- [ ] Only attendants can see an event’s message board, read a post’s core information (author, content, postedAt), and post to the event’s message board.
- [ ] Managers and the authors can remove posts.
- [ ] The author, event, and content of a post can only be set initially.
- [ ] Managers can review posts of events they manage.

### Review Process
- [ ] Posts on an event can be reviewed.
- [ ] Anyone who can read a post’s content, can flag it for review.
- [ ] When a post is reviewed positively, its
flag is cleared.
- [ ] If a post is reviewed negatively, its flag is cleared and the post is locked. 
- [ ] Those who can review a post can see whether it has been flagged and read its content and author.
- [ ] A post’s lock, and all information of locked
posts can only be read by those who can review the respective post.
- [ ] Locked posts cannot be deleted.

### Persons
- [ ] Users can see any other user’s core information (name, surname, username, role).
- [ ] Users can edit their password, and their own core information except their role.
- [ ] Each user can see the events they own, manage, attend, or requested access to, the posts they authored, the categories they subscribed to, and the invitations they received or sent.
- [ ] The categories moderated by a user can be seen by everyone.

### Categories
- [ ] Users can see who moderates a category. 
- [ ] Moderators can decide to remove themselves as the moderator of a category.
- [ ] Categories can be seen and their name, events and moderators can be read by everyone, but only moderators of a category can see its subscribers.

## Role-Specific Permissions

### None Role

### Premium Users

### Moderators

### Administrators
