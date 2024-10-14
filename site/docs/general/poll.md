---
sidebar_position: 1
---

# Poll

This is the poll command, with this command you can generate a custom poll, for a determined period of time or indefinetly and close it whenever you want.

## Usage

:::note

if a command includes `duration` and `format` as optional parameters, it means that if one is set the other becomes required, otherwise both remain optional.

:::
`/poll <description> <channel> {duration} {format}`

![poll command img](./img/pollCommand.png)

## Explanation

This command has 2 required parameters and 2 optional parameters.

### Required parameters

* description: This parameter determines the description of the poll, it has a maximum lenght of 250 characters.
* channel: This parameter determines the channel in which the poll will be sent, it must be a text only channel and the bot must have access and permissions to send messages and attachments to it.

### Optional parameters

* duration: This parameter determines the duration of the poll (this will be taken in seconds, minutes, hours or days depending on the format). 
* format: This parameter determines the format in which the duration will be taken.


## Potential errors

### Duration is sent but format is not sent / Format is sent but duration is not sent

This error happen when only one of the two optional parameters is sent, either duration or format but not both.
To fix it simply send the two parameters.