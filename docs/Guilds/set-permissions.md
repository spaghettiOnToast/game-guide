---
sidebar_label: 'Set Permissions'
sidebar_position: 7
---

# Set Permissions

Set permissions for the guild. This will be the contract addresses and selectors that the members of the guild can interact with. You can check these on the game contracts.

![setpermissions](/img/guilds/setpermissions.png)

:::warning IMPORTANT

For security, permissions can only be set **once**. Future governance will allow permissions to be updated, while agreed with all members of the guild.

:::

To mint a realm, permissions need to be set to allow the guild to make this execution. In set permissions, add **mint** (selector) and the realms contract **0x076bb5a142fa1d9c5d3a46eefaec38cc32b44e093432b1eb46466ea124f848a5** (realms contract address) then set permissions.

