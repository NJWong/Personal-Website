---
 layout: post
 title:  "How We Do Requirements"
 date:   2016-03-28
 category: blog
---
# The Term "Requirements"
Call me picky, but I've never really been a big fan of using the term **requirements** in software projects. According to the Software Engineering Body of Knowledge (SWEBOK) version 3.0:

> Software Requirements express the needs and constraints placed on a software product that contribute to the solution of some real-world problem.

I don't have an issue with the definition given above. Far from it in fact - every project has *"needs"* and *"constraints"*, otherwise it both pointless and is not well defined. My beef is with the word ***"requirement"*** as, to me, it implies that thing is essential for the system to function. A requirement is either met, or not met - there is no in between in my eyes. If it is not met, then the system is missing an essential element and thus does not perform as needed.

Of course, there are some actual requirements (functional or non-functional) that are system critical. In these cases, I would be comfortable calling these elements requirements. But I feel using it as a blanket name for critical and non-critical elements is careless.

# Our Naming Conventions
For our Full Year Project we are using a naming convention that works well for our development process. For reference, we're using Scrum-like approach with some XP practices build in.

**Backlog Items**

High-level work item that the customer wants to see in the software product. Generally we only tackle one backlog item per sprint, but we might sneak in two if they are small enough. We give each backlog item a unique ID.

*Example*

> [CQ] Call Queue

**Sprint Task**
The individual work units that are required to complete a backlog item. These are small enough to estimate individually and contribute to the sprint burndown chart. We give each sprint task a unique ID based on the backlog item it is related to.

*Example*

> [CQ-03] Display phone number for calls on the call queue

**User Stories**

Personally I think the ***As a \<type of user >, I want \<some goal> so that \<some reason>*** User Story template has its place in Agile projects. We've done fine so far without following this template, however my team is open to experimentation further down the line. I think what's more important is the discussion that a user story inspires. It helps to stimulate discussion about the "who", "what", and "why" of a feature. We have this conversation with our stakeholders in different ways (drawing lots of diagrams mostly) and that helps us drill down on the important details.

# Conclusion
> That which we call a rose by any other name would smell as sweet

At the end of the day, it doesn't really matter what naming convention we go with, given some conditions are met:

1. Everyone understands and correctly uses the chosen naming convention
2. The information sufficiently captures the what the customer needs
3. There is a clear distinction between system critical and non-critical elements