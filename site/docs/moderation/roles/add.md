---
sidebar_position: 0
---

# Add role

This is the add subcomand, it allows you to add a role to the specified user, for this, the bot needs to have it's own role avobe the role you want to assign.

## Usage

`/roles add <user> <role>`

![roles add Command](img/rolesAddCommand.png)

## Explanation

This command has 2 required parameters, the user to assign the role to, and the rol to be assigned.

### Required parameters

* user: This can be any user in the server who doesn't have the role (sending someone who has the role does nothing).
* role: This role must be below the bot's role, otherwise the bot will not have permission to assign it and a error will be displayed.