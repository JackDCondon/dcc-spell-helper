# dcc-spell-helper

## General

This is a macro generator for importing spells to Foundry VTT. 

Requirements: You need to have the EasyTable by Blitz module installed and activated. 

1. Make sure you have a compendium named "dcc-spell-tables" or type your own compendium name in the compendium name text field. (It must be a RollTable type compendium)
2. Make sure you have a compendium named "dcc-spells" or type your own compendium name in the item compendium name text field. (It must be a Item type compendium)
3. Copy paste from PDF, from the spell name and forward until you reach the next spell.
4. Convert >> cleans up the text,  double check make sure it looks "nice"
5. Macro >> Creates a Macro you can copy paste and run in Foundry VTT  by open up one of the macro buttons, paste,  choose script in the dropdown and then click execute.

Expected result: All RollTbales will be created then imported to your compendium as well. The main RollTable description for the spell will receive the nice formatting from Christian Ovseniks guide. With all tables linked. Then the spell item will be created > imported to your compendium and then linked to your main rolltable. 


## Good to know

OBS there is probably A LOT of bugs to sort out yet. This is a very untested version. If it only partially works delete all tables in Roll Tables section and possibly in your compendium and try again :slight_smile: i will test it further during the week and sort out more bugs. I'm certain that some spells wont work due to the formatting. 

Warning! Spamming the macro will potentially create a lot of RollTables.

## Known bugs

Sometimes the range of the dice is not properly recognized and can result i a table without a range.

Does not work properly with 
* Make Potion
* Sword Magic
* Turn to Stone

## Future
Mainly bug fixes
