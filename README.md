# Brief for the candidate:

## Overview
BrightHR has a daily reminder feature. This uses email to provide users and/or their managers with reminders of important upcoming events or things they need to take action on.  

For example:

| Reminder type | Recipients |
|---------------|------------|
| Unread documents (e.g. contract amendment) | User |
| Work anniversary | User & their managers |
| Missing emergency contact details | User & their managers |
| Employee's birthday | Managers |

There are over twenty reminder types.

Running a database query to collate the data for a reminder type can take widely differing times - from several seconds for a simple reminder in our smallest region to over forty minutes for complex reminders on large regions.

Some reminders are sent more than once, e.g. an employee's birthday reminder is sent one week before the event and on the day of the event. Unread document reminders are sent every day until the condition is satisfied.

The emails are due to be sent between 7-8am in the morning.

BrightHR operates in the UK, the Republic of Ireland, Canada, Australia and New Zealand - with data centres across these regions.

Any one company and it's users are in one region.

## Instructions

Design a solution that would deliver daily reminders to our users.

We _do not_ want to see working code - we are more interested in a broad end-to-end solution - its architecture, key principles and the way you came to decisions about the way it would work.

We _do_ want you to talk about the design and the thinking that got you to it - this will be a dialogue, we will be asking questions and you can ask questions of the interviewer too.

Note down assumptions you make and constraints you might hit.

BrightHR uses Microsoft Azure with a .NET back-end stack, but you can base your solution on any tech stack, around another cloud provider or on-prem if that's where your experience lies.

You can explain your solution in any way you feel comfortable - pen and pad, on a whiteboard, a slide deck, Visio diagrams, voice and gestures etc. Please let us know if you want a whiteboard to present with.

You _do not_ have to submit anything in advance of your interview.
