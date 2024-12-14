---
sidebar_position: 1
---

# Remove role

This is the remove subcomand, it allows you to remove a specific role from a user.

## Usage

`/roles remove <user> <role>`

![roles remove Command](img/rolesRemoveCommand.png)

## Explanation

This command has 2 required parameters, the user to remove the role from, and the rol to be removed.

### Required parameters

* user: This can be any user in the server who has the role, if the user doesn't have the role, nothing will happen.
* role: This role must be below the bot's role, otherwise the bot will not have permission to remove it and a error will be displayed.