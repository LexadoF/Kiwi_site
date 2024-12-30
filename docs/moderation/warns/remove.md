---
sidebar_position: 2
---

# Remove warn

This is the remove subcommand, it allows you to remove a warning from a user, for this you will need the warning id.
:::note

Warning id's are currently calculated dinamically, for this reason you must check using the review command before removing a warning

:::

## Usage

`/warns remove <user> <id>`

![warns add Command](img/warnsRemoveCommand.png)

## Explanation

This command has 2 required parameters, the user and the id.

### Required parameters

* user: This can be any user in the server who has warns.
* id: This is the specific id of the warning you want to remove, due to the list being assigned dinamic ids, if a user for example has 3 warnings and delete the number 2, the warning number 3, now becomes warning number 2. For this reason, make sure to check the warnings with the review comand before executing.