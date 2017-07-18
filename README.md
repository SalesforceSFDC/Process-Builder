# Salesforce Process Builder

 * [Process Builder Overview](https://help.salesforce.com/articleView?id=process_overview.htm&language=en_US&type=0)
 * [Process Limits and Considerations](https://help.salesforce.com/articleView?id=process_considerations.htm&language=en_US&type=0)
 * [Automate Key Business Processes with Lightning Process Builder](http://pages.mail.salesforce.com/achievemore/automateprocesses/?utm_source=trailhead&utm_medium=resources&utm_campaign=072016)
 * [Publishing Salesforce Data to REST APIs with Lightning Process Builder](https://www.youtube.com/watch?v=pxaDZO_uLqA&spfreload=5)
 * [Slack WebHooks](https://optimizely.slack.com/apps/A0F7XDUAZ-incoming-webhooks)
 * Named Credentials - a configuration item that allows you to define the credentials that should be used when making a callout to a particular external service, either per user or for all users.
 
Automated processes in the Process Builder consist of:
 * Criteria that determine when to execute action groups
 * Immediate and scheduled actions to execute when those criteria are met

Any change that causes a record to match the criteria automatically triggers the action group.

A schedule lets the process know that it must wait to execute the associated actions. Because you can configure multiple schedules for the same criteria node, each schedule has its own list of actions to execute.

To add scheduled actions to your process, you have two options:
 * Start the process only when a record is created (1). Select this option when you choose an object for your process.
 * Start the process when a record is created or edited (2). In addition, select the advanced option to execute actions only when specified changes are made (3) when you add criteria to your process.
 
A process can have up to 50 versions, but only one version of a process can be active.


 * 
