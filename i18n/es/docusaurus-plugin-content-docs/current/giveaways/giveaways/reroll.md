---
sidebar_position: 3
---

# Reroll giveaway

:::warning

When executing this subcommand new winners will be selected taking into account the `winners` parameter specified in the create / edit commands. For example if 5 winners were set, this re roll will select 5 new winners.
Previous winner data might be lost after the re roll is performed, be careful.

:::

This subcommand will allow you to reroll a giveaway. For this you will need to provide the giveaway message id. If no valid giveaway is found in the message with the id given, you will get an error and nothing will happen.

## Usage

`/giveaways reroll <message-id>`

![giveaway command img](./img/giveawaysCommandReroll.png)