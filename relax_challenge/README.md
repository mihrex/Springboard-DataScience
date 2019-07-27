## Relax Inc. Data Science Sample Take Home Challenge ##

This is a practice take home challenge from Relax Inc.

The data is available as two attached CSV files: takehome_user_engagement. csv takehome_users . csv The data has the following two tables:

1. A user table ( "takehome_users" ) with data on 12,000 users who signed up for the product in the last two years. This table includes:
2. name: the user's name
3. object_id: the user's id
4. email: email address
5. creation_source: how their account was created. This takes on one of 5 values:
 - PERSONAL_PROJECTS: invited to join another user's personal workspace
 - GUEST_INVITE: invited to an organization as a guest (limited permissions)
 - ORG_INVITE: invited to an organization (as a full member)
 - SIGNUP: signed up via the website
 - SIGNUP_GOOGLE_AUTH: signed up using Google Authentication (using a Google email account for their login id)
6. creation_time: when they created their account
7. last_session_creation_time: unix timestamp of last login
8. opted_in_to_mailing_list: whether they have opted into receiving marketing emails
9. enabled_for_marketing_drip: whether they are on the regular marketing email drip
10. org_id: the organization (group of users) they belong to
11. invited_by_user_id: which user invited them to join (if applicable).
12. A usage summary table ( "takehome_user_engagement" ) that has a row for each day that a user logged into the product.

Defining an "adopted user" as a user who has logged into the product on three separate days in at least one sevenday period , identify which factors predict future user adoption .

We suggest spending 12 hours on this, but you're welcome to spend more or less. Please send us a brief writeup of your findings (the more concise, the better no more than one page), along with any summary tables, graphs, code, or queries that can help us understand your approach. Please note any factors you considered or investigation you did, even if they did not pan out. Feel free to identify any further research or data you think would be valuable.
