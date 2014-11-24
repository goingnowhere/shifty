#Shifty

## *A shift management system for Nowhere*


## Problems trying to solve
* Nowhere is a volunteer-based event, and there's a range of tasks and roles that need filling each year.

* Keeping track of what (as a volunteer) you've signed up for can be difficult. 

* Knowing that the shift has been accepted is sometimes lost.

* Assigning roles can be tiresome not knowing other shift  patterns as a shift-manager. 

* Remembering about shifts can be troublesome as a participant.

* Knowing what shifts have been assigned is also an issue.

* Documents get lost / inaccessible on-site. Lots of different documents are in circulation.

* One system is needed for everything, and for all of the cases

## Users
* Participants
* Role holders with shifts
* Production managers (for the event)
* Leads (on duty/off duty)


## Requirements
### Technical
* Internet based
* Easy to use for all types of user with basic internet literacy
* Programming language agnostic, depending on skills
* Reliable, well written, easy to maintain
* Permissions based:
    * user can only see their entries
    * shift manager can only edit theirs?
    * site admin can do all
* Should probably use oauth -- but fall-back to password
login if needed
* Export to CSV essential (for admins)
* Export to JSON desirable (tied to permissions)
* Ability to send emails to people from within the app:
    * individually
    * shift pattern
    * globally
* Transactional emails (on signup, on ack, on allocation, or
reshuffle, 10 days before…)

### Legislative/Regulatory
* Secure, without information leaks
* Hosted within EEA or Safe Harbor
* Should only collect the information we need

### UX
* Ability to print (en masse) details for shifts in an expected size (e.g. for wristbands per conscript)
* Reporting: should be able to clearly see:
    * blackspots in shifts
    * those over-working
    * who's on now / next easily/quickly


### Business Logic
* Rules (can't do > 18 concurrent hours; gender balance)
* Different rules for different posts

### Social?
* Is this needed? Pre-filled Tweets ("I just signed up for a shift at
Nowhere: buddy with me") maybe?
