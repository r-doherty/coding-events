# coding-events

-- App Purpose 
This is a simple web-app aimed at providing an outlet for listing various coding events,
and details about said events including contact e-mail, a brief description, and various
tag and category determinations. Built with Java and liked to MySQL database.

-- Current State of the App
The app currently allows users to create events, including inputting information for their
descriptions, contact emails, and categories. Users can also delete said events and create
custom options for the categories which events can be designated into.

-- Future Improvements
The first major overhaul of this app would need to be creating a 'User base' by adding a'Person'
class. This means implementing an authentication and login process for individuals to have
unique access to moderating their designated events or event listings. This would require creating
appropriate user info fields (passwords, usernames, emails, etc.) as well as the appropriate
getter and setter methods for those fields, and an established relationship to the Event, 
EventCategory, and Tags classes, depending on the desired functionality. A many to one relationship 
(if you were tracking potential attendees). A one to many relationship could be valuable for 
situations where you want a single user to be able to edit events or be a contact, etc. (host). A
many to many relationship if this was a forum or community app where users could sign-up to
receive updates on multiple events and interact with communities while the Events also were tracking
many users and their interactions with the event page.
