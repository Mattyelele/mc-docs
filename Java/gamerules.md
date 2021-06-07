# Gamerules

Gamerules can control a varety of aspects of gameplay and provide customisation for server owners.

## Setting the value

By using the command `/gamerule <rule name> <value>`

To receive the current value you can use `/gamerule <rule name>`

- `Rule Name` is the name specific for the gamerule that you would like to set or view. You can find a list of the gamerules below.
- `Value` is the value you wish to assign to a specific rule name. In most cases this is either `true` or `false`, sometimes it could be a number.

You can find More information on Gamerules on the [Minecraft Wiki](https://minecraft.fandom.com/wiki/Commands/gamerule).

<table>
<thead>
<tr style="height: 41px;">
<th style="height: 41px;">Rule Name</th>
<th style="height: 41px;">Description</th>
<th style="height: 41px;">Possible Values</th>
<th style="height: 41px;">Java Edition</th>
<th style="height: 41px;">Bedrock Edition</th>
<th style="height: 41px;">Version Added</th>
</tr>
</thead>
<tbody>
<tr style="height: 21px;">
<td style="height: 21px;">announceAdvancements</td>
<td style="height: 21px;">Whether advancements should be announced in chat</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">❌</td>
<td style="height: 21px;">1.12</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">commandBlocksEnabled</td>
<td style="height: 21px;">Whether command blocks should be enabled in-game</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">❌</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">1.7.0</td>
</tr>
<tr style="height: 41px;">
<td style="height: 41px;">commandBlockOutput</td>
<td style="height: 41px;">Whether command blocks should notify admins when they perform commands</td>
<td style="height: 41px;">true/false</td>
<td style="height: 41px;">✔️</td>
<td style="height: 41px;">✔️</td>
<td style="height: 41px;">1.4.2</td>
</tr>
<tr style="height: 41px;">
<td style="height: 41px;">disableElytraMovementCheck</td>
<td style="height: 41px;">Whether the server should skip checking player speed when the player is wearing elytra</td>
<td style="height: 41px;">true/false</td>
<td style="height: 41px;">✔️</td>
<td style="height: 41px;">❌</td>
<td style="height: 41px;">1.9</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">disableRaids</td>
<td style="height: 21px;">Whether raids are disabled or not</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">❌</td>
<td style="height: 21px;">1.14.3</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">doDaylightCycle</td>
<td style="height: 21px;">Whether the day-night cycle and moon phases progress</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">1.6.1</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">doEntityDrops</td>
<td style="height: 21px;">Whether entities that are not mobs should have drops</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">1.8.1</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">doFireTick</td>
<td style="height: 21px;">Whether fire should spread and naturally extinguish</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">1.4.2</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">doInsomnia</td>
<td style="height: 21px;">Whether phantoms can spawn in the nightmare</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">1.15</td>
</tr>
<tr style="height: 41px;">
<td style="height: 41px;">doImmediateRespawn</td>
<td style="height: 41px;">Players respawn immediately without showing the death screen. (Bedrock: <code>immediateRespawn</code>)</td>
<td style="height: 41px;">true/false</td>
<td style="height: 41px;">✔️</td>
<td style="height: 41px;">✔️</td>
<td style="height: 41px;">1.15</td>
</tr>
<tr style="height: 41px;">
<td style="height: 41px;">doLimitedCrafting</td>
<td style="height: 41px;">Whether players should only be able to craft recipes that they've unlocked first</td>
<td style="height: 41px;">true/false</td>
<td style="height: 41px;">✔️</td>
<td style="height: 41px;">❌</td>
<td style="height: 41px;">1.12</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">doMobLoot</td>
<td style="height: 21px;">Whether mobs should drop items</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">1.4.2</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">doMobSpawning</td>
<td style="height: 21px;">Whether mobs should naturally spawn</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">1.4.2</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">doPatrolSpawning</td>
<td style="height: 21px;">Whether patrols can spawn</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">❌</td>
<td style="height: 21px;">1.15.2</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">doTileDrops</td>
<td style="height: 21px;">Whether blocks should have drops</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">1.4.2</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">doTraderSpawning</td>
<td style="height: 21px;">Whether wandering traders can spawn</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">❌</td>
<td style="height: 21px;">1.15.2</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">doWeatherCycle</td>
<td style="height: 21px;">Whether the weather will change</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">1.11</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">drowningDamage</td>
<td style="height: 21px;">Whether the player should take damage when drowning</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">1.15</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">fallDamage</td>
<td style="height: 21px;">Whether the player should take fall damage</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">1.15</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">fireDamage</td>
<td style="height: 21px;">Whether the player should take fire damage</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">1.15</td>
</tr>
<tr style="height: 41px;">
<td style="height: 41px;">forgiveDeadPlayers</td>
<td style="height: 41px;">Makes angered neutral mobs stop being angry when the targeted player dies nearby.</td>
<td style="height: 41px;">true/false</td>
<td style="height: 41px;">✔️</td>
<td style="height: 41px;">❌</td>
<td style="height: 41px;">1.16</td>
</tr>
<tr style="height: 41px;">
<td style="height: 41px;">keepInventory</td>
<td style="height: 41px;">Whether the player should keep items in their inventory after death</td>
<td style="height: 41px;">true/false</td>
<td style="height: 41px;">✔️</td>
<td style="height: 41px;">✔️</td>
<td style="height: 41px;">1.4.2</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">logAdminCommands</td>
<td style="height: 21px;">Whether to log admin commands to server log</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">❌</td>
<td style="height: 21px;">1.8</td>
</tr>
<tr style="height: 41px;">
<td style="height: 41px;">maxCommandChainLength</td>
<td style="height: 41px;">Determines the number at which the chain command block acts as a "chain"</td>
<td style="height: 41px;">number</td>
<td style="height: 41px;">✔️</td>
<td style="height: 41px;">✔️</td>
<td style="height: 41px;">1.12</td>
</tr>
<tr style="height: 81px;">
<td style="height: 81px;">maxEntityCramming</td>
<td style="height: 81px;">The maximum number of pushable entities another entity can try to push, before taking suffocation damage. Setting to 0 disables the rule. Affects players and mobs only (excluding bats)</td>
<td style="height: 81px;">number</td>
<td style="height: 81px;">✔️</td>
<td style="height: 81px;">❌</td>
<td style="height: 81px;">1.11</td>
</tr>
<tr style="height: 81px;">
<td style="height: 81px;">mobGriefing</td>
<td style="height: 81px;">Whether creepers, zombies, endermen, ghasts, withers, ender dragons, rabbits, sheep, and villagers should be able to change blocks and whether villagers, zombies, skeletons, and zombie pigmen can pick up items</td>
<td style="height: 81px;">true/false</td>
<td style="height: 81px;">✔️</td>
<td style="height: 81px;">✔️</td>
<td style="height: 81px;">1.4.2</td>
</tr>
<tr style="height: 61px;">
<td style="height: 61px;">naturalRegeneration</td>
<td style="height: 61px;">Whether the player can regenerate health naturally if their hunger is full enough (doesn't affect external healing, such as golden apples, the Regeneration effect, etc.)</td>
<td style="height: 61px;">true/false</td>
<td style="height: 61px;">✔️</td>
<td style="height: 61px;">✔️</td>
<td style="height: 61px;">1.6.1</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">pvp</td>
<td style="height: 21px;">Whether the player can fight with other players</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">❌</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">1.0.5</td>
</tr>
<tr style="height: 61px;">
<td style="height: 61px;">randomTickSpeed</td>
<td style="height: 61px;">How often a random block tick occurs (such as plant growth, leaf decay, etc.) per chunk section per game tick. 0 will disable random ticks, higher numbers will increase random ticks</td>
<td style="height: 61px;">number</td>
<td style="height: 61px;">✔️</td>
<td style="height: 61px;">✔️</td>
<td style="height: 61px;">1.8</td>
</tr>
<tr style="height: 61px;">
<td style="height: 61px;">reducedDebugInfo</td>
<td style="height: 61px;">Whether the debug screen shows all or reduced information; and whether the effects of F3+B (entity hitboxes) and F3+G (chunk boundaries) are shown</td>
<td style="height: 61px;">true/false</td>
<td style="height: 61px;">✔️</td>
<td style="height: 61px;">❌</td>
<td style="height: 61px;">1.8</td>
</tr>
<tr style="height: 61px;">
<td style="height: 61px;">sendCommandFeedback</td>
<td style="height: 61px;">Whether the feedback from commands executed by a player should show up in chat. Also affects the default behavior of whether command blocks store their output text</td>
<td style="height: 61px;">true/false</td>
<td style="height: 61px;">✔️</td>
<td style="height: 61px;">✔️</td>
<td style="height: 61px;">1.8</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">showCoordinates</td>
<td style="height: 21px;">Whether the player's coordinates are displayed</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">❌</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">Unknown</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">showDeathMessages</td>
<td style="height: 21px;">Whether a message appears in chat when a player dies</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">1.8</td>
</tr>
<tr style="height: 61px;">
<td style="height: 61px;">spawnRadius</td>
<td style="height: 61px;">The number of blocks outward from the world spawn coordinates that a player will spawn in when first joining a server or when dying without a spawnpoint</td>
<td style="height: 61px;">number</td>
<td style="height: 61px;">✔️</td>
<td style="height: 61px;">✔️</td>
<td style="height: 61px;">1.9</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">spectatorsGenerateChunks</td>
<td style="height: 21px;">Whether players in spectator mode can generate chunks</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">❌</td>
<td style="height: 21px;">1.9</td>
</tr>
<tr style="height: 21px;">
<td style="height: 21px;">tntExplodes</td>
<td style="height: 21px;">Whether TNT will explode or not after activation</td>
<td style="height: 21px;">true/false</td>
<td style="height: 21px;">❌</td>
<td style="height: 21px;">✔️</td>
<td style="height: 21px;">Unknown</td>
</tr>
<tr style="height: 61px;">
<td style="height: 61px;">universalAnger</td>
<td style="height: 61px;">Makes angered neutral mobs attack any nearby player, not just the player that angered them. Works best if you disable <code>forgiveDeadPlayers</code>.</td>
<td style="height: 61px;">true/false</td>
<td style="height: 61px;">✔️</td>
<td style="height: 61px;">❌</td>
<td style="height: 61px;">1.16</td>
</tr>
<tr style="height: 41px;">
<td style="height: 41px;">showTags</td>
<td style="height: 41px;">Hides the "Can place on" and "Can destroy" block lists from item lore.</td>
<td style="height: 41px;">true/false</td>
<td style="height: 41px;">❌</td>
<td style="height: 41px;">✔️</td>
<td style="height: 41px;">1.14.0</td>
</tr>
</tbody>
</table>