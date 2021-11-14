

# Event platfrom -  Security Model in ActionGUI
## Entity Permissions

### Core Information
- [x] Users (i.e., anyone who is logged in) can create public events.
- [x] Everyone (i.e., also users who are not logged in) can read a public event’s core information (title, description, location, date, owner) and any event’s categories
- [x] For private events, only its attendants and users invited to the event can read that information.
- [x] Only managers of an event can edit the core information with the exception of the owner who cannot be changed but only set initially

### Attendants
- [x] For public events, users can see who is attending them and who is managing them.
- [x] For private events, only attendants and those who have an invitation pending can read that information.
- [x] Only the owner can promote attendants to managers and demote managers to attendants.
- [x] Managers can remove attendants from the event, but only if the attendant is not a manager.
- [x] They also can add those who requested to join an event as attendants.
- [x] Everyone besides the owner can remove themselves from attending the event.
- [x] Everyone can add themselves as attendant to a public event, if they have been invited.

### Invitations & Requests
- [x] Everyone can request to join a public event and
cancel their requests.
- [x] Only event managers can invite users to events they manage, cancel invitations, and accept and deny request.
- [x] An invited user can accept or decline the invitation (in both cases, the invitation is deleted). Managers can see all invitations and requests for the respective event.
- [x] Invitations are read-only, i.e., once they have been assigned, the values of invitee, invitedBy, and event cannot be changed.

### Message Board
- [x] Only attendants can see an event’s message board, read a post’s core information (author, content, postedAt), and post to the event’s message board.
- [x] Managers and the authors can remove posts.
- [x] The author, event, and content of a post can only be set initially.
- [x] Managers can review posts of events they manage.

### Review Process
- [x] Posts on an event can be reviewed.
- [x] Anyone who can read a post’s content, can flag it for review.
- [x] When a post is reviewed positively, its flag is cleared.
- [x] If a post is reviewed negatively, its flag is cleared and the post is locked.
- [x] Those who can review a post can see whether it has been flagged and read its content and author.
- [x] A post’s lock, and all information of locked posts can only be read by those who can review the respective post.
- [x] Locked posts cannot be deleted.

### Persons
- [x] Users can see any other user’s core information (name, surname, username, role).
- [x] Users can edit their password, and their own core information except their role.
- [x] Each user can see the events they own, manage, attend, or requested access to, the posts they authored, the categories they subscribed to, and the invitations they received or sent.
- [x] The categories moderated by a user can be seen by everyone.

### Categories
- [ ] Users can see who moderates a category.
- [ ] Moderators can decide to remove themselves as the moderator of a category.
- [ ] Categories can be seen and their name, events and moderators can be read by everyone, but only moderators of a category can see its subscribers.

## Role-Specific Permissions

### None Role

### Premium Users

### Moderators

### Administrators
