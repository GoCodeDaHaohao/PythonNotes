#  AB Test Analysis Project 

To encourage more referrals, the product team is running an experiment on the iOS app, called “ios_referral_experiment”, that tests adding new links to the referral invite page. The experiment has 3 groups: the “control” group has no new link; the “tab_only” group has a new navigation tab that links to the page; and the “tab_settings” group has both a new navigation tab and a new link in the settings.  What are the results of this experiment, and what would you recommend to the team?

### Description of the data
Included with this exercise is a set of csv files containing data for the following tables.
### split_test_exposures
This table includes all occurrences when a user is exposed to an experiment.
- user_id : unique id for the user
- exposed_time : time when the user was exposed to the experiment
- split_test_name : name of the split test the user was exposed to
- split_test_group : the split test group the user was assigned to
### events
This table includes click and view events in the UI.
- user_id : unique id for the user
- event_time : time when the event occurred
- event_type : the type of event that happened
- “ referral_page_view ”: user views the page for sending referral invites
- “ referrer_page_invite_action ”: users clicks the button to send a referral invite
- event_type_button : the type of button the user clicks for the event
