Feature request: Ability to handle task and lane assignment before a user account has been created.  Resolve lane ownership and group members as late as possible, so that new users added to existing groups can complete current tasks assigned to that group.

It seems to work if there is already at least one user assigned to the group
(since the group then exists), but if no one from the group has signed in, we
get:

NoPotentialOwnersForTaskError: Could not find a group with name matching lane: [group_name]

Look through the codebase and devise a plan to fix this, writing the
implementation plan to plan.md
