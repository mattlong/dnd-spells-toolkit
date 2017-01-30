## Spell card generation pipeline

* Grab CSV of relevant spells from [http://hardcodex.ru/cleric/](http://hardcodex.ru/cleric/)
* Craft list of expected base spells and subclass-specific spells in expected-base-spells.csv, expected-tempest-spells.csv, etc.
    * For base spells copy pasta, this site seemed to be accurate: [https://www.5thsrd.org/spellcasting/spell_lists/cleric_spells/](https://www.5thsrd.org/spellcasting/spell_lists/cleric_spells/)
    * For subclass specific, deal with it, yo
* Specify all these CSVs as inputs to the "Cleric Spells" iPython Notebook
* Make cards with [http://crobi.github.io/rpg-cards/generator/generate.html](http://crobi.github.io/rpg-cards/generator/generate.html)
    * If that site is no longer available, should be able to recreate it from [https://github.com/mattlong/rpg-cards](https://github.com/mattlong/rpg-cards)
    * US letter, 3.5" x 5.0", 2x2 per page, Front side only, white, white, Use small front icons, dimgray, 13pt title
    * Be sure to specify an icon for extra fun. "ship-wheel" is my Tempest icon
* Click "Delete all"
* Click "Load from file" and specify JSON file outputed from notebook
* Click "Generate"
* Review cards
    * If any descriptions are too long to fit on card, you can override them by following the examples in overrides.txt
* If printing in Chrome, make sure "Background graphics" is enabled
* Cast Zone of Truth


### Other stuff

* Not entirely sure what this is for: [https://github.com/roryscarson/dndnext_spell_server](https://github.com/roryscarson/dndnext_spell_server)
* https://www.reddit.com/r/dndnext/comments/2qo2em/i_made_spell_cards_for_every_spell_in_the_phb/
* https://www.reddit.com/r/dndnext/comments/2qmidi/dd_5th_edition_sorcerer_spell_list/
* http://donjon.bin.sh/5e/spells/
* https://www.dnd-spells.com/spells/class/cleric
