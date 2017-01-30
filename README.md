## Spell card generation pipeline

* Grab CSV of relevant spells from [http://hardcodex.ru/cleric/](http://hardcodex.ru/cleric/)
* Craft list of expected base spells and subclass-specific spells in expected-base-spells.csv, expected-tempest-spells.csv, etc.
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
