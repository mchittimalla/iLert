Hello, I am Manoj, ILert product specialist, I am giving demo about iLert tool and its features 

ILert is an on-call management tool. It integrates monitoring systems as alert sources in iLert
It helps teams to reduce response times to critical incidents. It sends prioritized alerts to stake holder and make sure that stakeholder never miss critical incidents. and create tickets in external incident management tools.
The Core features of iLert, which helps us in day to day activities are

#1.	iLert user – onboarding the iLert user
The user who want to use iLert must raise a user onboarding service request, and iLert admins will add the user in Azure Ad and will update the status to user in comments section of service request and user has to go to iLert and should login through SSO.

2.	iLert team – onboarding the iLert team 
Team will be created with the name provided by requestor in service request and will add requestor as team admin so that team admin can create alert sources, escalation policies and oncall schedules

3.	Alert source / inbound integration
An alert source represents the connection between your tools usually a monitoring system, a ticketing tool, or an application and iLert. We often call this as inbound integration
a.	Tools integrations
b.	Email Integrations
c.	API Integrations
d.	SMS integrations
e.	Heartbeat Monitoring
I will create an alert source in this demo after covering about oncall schedules and escalation policies 

4.	Oncall schedules
On-call schedules determine who will be notified when an incident is created based on the time of day. Only one user per schedule can be on-call at a time. Oncall schedule should be added in escalation policy then only members will be notified about incidents.
I will show you how to create oncall schedule for your team

While creating oncall schedules: 
Any changes to schedules apply to current and future dates only. Shifts that are in the past cannot be deleted or modified. Schedules can be embedded into any calendar application that supports the iCal format.
You can create and modify schedule.


You can override your planned schedule 
•	when a user becomes sick, goes on vacation, or would like to swap a shift with another user
•	scheduling different shifts for holidays


5.	Escalation policy
An escalation policy connects an alert source with the users that are responsible for this alert source. It defines which users or on-call schedules should be notified when an incident is created. It also determines who shall be notified if the On-call person misses the alerts. 
I will show you how to create oncall schedule 
6.	Notifications
Another important feature is setting up your notifications. In iLert, each user must define in his profile how he should be notified of an incident
      	iLert supports the following notification channels:
•	E-mail
•	SMS
•	Phone calls
•	iPhone and Android push notification
Notifications in iLert are bi-directional, that is, you can respond to a notification using the same channel on which you were notified (without logging into iLert).
You have the following response options:
1.	Acknowledge the incident
2.	Mark the incident as resolved
3.	Escalation to the next user
7.	Connectors and incident actions / outbound integrations
Connectors and incident actions allow you to extend your incident response and communication to other tools. They allow you to either manually or automatically perform actions on incidents, such as
•	Create ticket in JIRA
•	Create incident in servicenow
•	Post a message in Slack, Teams
•	Post a webhook to a defined HTTP end point
•	Trigger a serverless function in AWS, GCP or Azure
A connector is created globally in iLert and usually contains all the information to connect with the target system (e.g. a URL, an API key or username and password, etc.)



