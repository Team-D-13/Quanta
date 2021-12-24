# Quanta

## Base Rules

Preparation - Once a game starts, all players load their decks. Afterwards, they place their Quanta Lords to their fields (CTRL+F3, see 'Quanta Lord' below). All players draw 5 cards for their starting hands. Afterwards, each player can mulligan - choose any amount of the cards from their starting hands, return them to the deck, shuffle the deck, then draw as many cards as they returned. All players set their life to 30. Finally, the turn order is decided by all players rolling a d1000 (CTRL+I). The turn order goes from the highest result to the lowest. All players start with 0 quanta/max quanta before their first turn takes place.

Turn Start & Quanta - At the start of each of your turns, you draw a card, increase your maximum quanta by 1, then set your quanta to your maximum quanta. Upkeep effects trigger at the start of your turn as well. All of these (drawing, quanta, upkeep) have the same timing - though the typical procedure is draw>set quanta>upkeep, some upkeep effects interact with drawing or start-of-turn quanta. Start-of-turn drawing and quanta-setting are not upkeep effects themselves! The maximum quanta cap is 10 under normal circumstances, but the actual amount of quanta you can have is uncapped.

Counters - Some cards' effects place counters. These interact with certain cards. Counters are universal and shared for any effects that interact with them. Since in-game red counters signify damage, signify your actual counters using a different color of counter in-game.

Flow - NOT YET IMPLEMENTED. Flow resets to 0 at the end of your turn. It increases by 1 each time you play a card during your turn. It is tracked using an orb, like the quanta indicators. Some cards interact with flow.

## Card Types

Quanta Lord - Accessed through your side deck (CTRL+F3), a Quanta Lord has a unique ability that can serve as a keystone or addition to your deck. Quanta Lords are placed far off from other cards you may play, in the middle row. If you have a unit with [Guard], your Quanta Lord cannot be attacked, otherwise it is an open target. Quanta Lords have 30 life. Once the life is lost, you lose the game.

Unit - Units are played to the middle row, or front row if they have guard. They can take damage, attack and be attacked. They have stats, for example 1/2. The 1 would be strength - the amount of damage the unit's attack inflicts. The 2 would be toughness - the amount of damage the unit can take before being destroyed. When a unit attacks, it is exerted. It also cannot exert (for either attacking or using an effect) on the turn it is played unless it has the swift ability. This also means a unit that activates its Exert effect cannot attack on the same turn. Damage is signified with red counters.

Support - Supports are played to the bottom row. They activate immediately and are then sent to the graveyard in most cases. A support can only be played during your turn.

Flash - A subtype of support. It can be played at any time and usually has a tactical effect. (Flash itself is also a keyword that other card effects may have, not to be confused with these 'Support - Flash' cards.)

Relic - A card that provides passive support. It is played to the bottom row and stays there. Relics may have passive effects, exert effects or something more gimmicky.

Equipment - NOT YET IMPLEMENTED. An equipment is first played similarly to a relic, but usually has no inherent effect. Once on the field, however, it can be attached to a unit. The attaching may have its own cost. Equipment effects usually trigger or become active once it is attached. Once the unit leaves the field, the equipment is not destroyed, and is instead simply unattached (unless itself or other relevant cards specify otherwise, of course).

## Factions

### Picking your Quanta Lord decides your faction. You can play neutral cards and cards of that faction...

Arcane - Focus on supports and hand/deck manipulation. Specialization in counters. Minor focus on relics and flashes. Somewhat all-rounded.

Science - Focus on relics and supports. Specialization in tokens. Minor focus on counters and non-unit damage/destruction. Very all-rounded.

Nature - Focus on powerful units and buffs. Specialization in life manipulation. Minor focus on graveyard manipulation and swarming. Decently all-rounded.

Outsider - Focus on graveyard manipulation. Specialization in void manipulation and sacrifice. Minor focus on milling, hand manipulation and tokens. Not very all-rounded.

## Quanta Keywords...

[Aura]              - Ignores the first instance of damage received (or attempt at destruction) and loses [Aura].

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

{Upkeep}:    Upkeep is triggered at the start of your turn with the same timing as your draw and quanta gain.

Exert:       Effects with this callback...exert the card. Cards un-exert at the start of your turn. It is wise to remember that attacking also exerts, and that units without [Swift] cannot exert on the turn they are played.
