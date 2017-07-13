# Salesforce Process Builder
Automated processes in the Process Builder consist of:
 * Criteria that determine when to execute action groups
 * Immediate and scheduled actions to execute when those criteria are met

Any change that causes a record to match the criteria automatically triggers the action group.

A schedule lets the process know that it must wait to execute the associated actions. Because you can configure multiple schedules for the same criteria node, each schedule has its own list of actions to execute.

To add scheduled actions to your process, you have two options:
 * Start the process only when a record is created (1). Select this option when you choose an object for your process.
 * Start the process when a record is created or edited (2). In addition, select the advanced option to execute actions only when specified changes are made (3) when you add criteria to your process.
 
A process can have up to 50 versions, but only one version of a process can be active.
