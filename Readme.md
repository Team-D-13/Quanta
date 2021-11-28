# Quanta

## Base Rules

First Turn - The player going first is decided by all players rolling a D1000 (CTRL+I). The player with the highest number goes first, the others follow order based on their numbers. On your first turn, draw 5 cards, return the ones you do not like, shuffle your deck and draw the amount you returned.

Quanta - At your first turn, you start with 1 quanta. Using the orbs below your life counter, you signify both current and maximum quanta. Your maximum quanta increases at the start of each of your turns, and your quanta is set to that amount. This is not an upkeep effect! Quanta is capped at 10 normally.

Following Turns - At the start of each turn after the first, you draw a card, increase your maximum quanta by 1 and set your quanta to that amount as noted above, then follow through with any upkeep effects you may have.

Counters - Some cards' effects place counters. These interact with certain cards. Counters are universal and shared for any effects that interact with them. Since in-game red counters signify damage, signify your actual counters using a different color of counter in-game.

Flow - NOT YET IMPLEMENTED. Flow resets to 0 at the end of your turn. It increases by 1 each time you play a card during your turn. It is tracked using an orb, like the quanta indicators. Some cards interact with flow.

## Card Types

Quanta Lord - Accessed through your side deck (CTRL+F3), a Quanta Lord has a unique ability that can serve as a keystone or addition to your deck. If you have a unit with [Guard], your Quanta Lord cannot be attacked, otherwise it is an open target. Quanta Lords have 30 life. Once the life is lost, you lose the game.

Unit - Units are played to the middle row, or front row if they have guard. They can take damage, attack and be attacked. They have stats, for example 1/2. The 1 would be strength - the amount of damage the unit's attack inflicts. The 2 would be toughness - the amount of damage the unit can take before being destroyed. When a unit attacks, it is exerted. It also cannot attack on the turn it is played unless it has the swift ability. This also means a unit that activates its Exert effect cannot attack on the same turn. Damage is signified with red counters.

Support - Supports are played to the bottom row. They activate immediately and are then sent to the graveyard in most cases. A support can only be played during your turn.

Flash - A subtype of support. It can be played at any time and usually has a tactical effect. (Flash itself is also a keyword that other card effects may have, not to be confused with these 'Support - Flash' cards.)

Relic - A card that provides passive support. It is played to the bottom row and stays there. Relics may have passive effects, exert effects or something more gimmicky.

Equipment - NOT YET IMPLEMENTED. An equipment is first played similarly to a relic. Once on the board, it can be attached to a unit (the attaching may have its own cost), upon which it and/or the unit gain effects.

## Factions

### Picking your Quanta Lord decides your faction. You can play netural cards and cards of that faction...

Arcane - Focus on supports and hand/deck manipulation. Specialization in counters. Minor focus on relics and flashes. Somewhat all-rounded.

Science - Focus on relics and supports. Specialization in tokens. Minor focus on counters and non-unit damage/destruction. Very all-rounded.

Nature - Focus on powerful units and buffs. Specialization in life manipulation. Minor focus on graveyard manipulation and swarming. Decently all-rounded.

outsider = Focus on graveyard manipulation. Specialization in void manipulation and sacrifice. Minor focus on milling, hand manipulation and tokens. Not very all-rounded.

## Quanta Keywords...

[Aura]              - Ignores the first instance of damage received and loses [Aura].

[Guard]             - One unit with [Guard] must be a target of an attack if present.

[Hidden]            - Cannot be targeted. Removed if it attacks or exerts.

[Swift]             - Can attack units and exert immediately.

[Pierce]            - When dealing excess damage to a unit, deals it to their quanta lord.

[Toxic]             - Any amount of damage dealt by this is lethal to units.

[Invulnerable]      - Does not take damage.

[Shroud]            - Untargetable by effects.

[Regenerate]        - Recovers all damage at the start of your turn.

[Drain]             - Damage dealt by this also heals your Quanta Lord the same amount.

[Pacifist]          - Cannot attack.

## Quanta Callbacks...

{Summon}:    Activated when entering play.

{Death}:     Activated if sent to the graveyard from the field.

{Attack}:    Activated when attacking.

{Defend}:    Activated when attacked.

{Battle}:    Activated when attacking or attacked.

{Echo}:      Activated at the start of your next turn.

{Upkeep}:    Upkeep triggers happen at the start of your turn.

Exert:       A card can be exerted to activate an effect if not exerted. Exerted cards are restored at the start of your turn.