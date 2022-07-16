# Custom creatures for Ready Set Dice

This will be a basic overview of how to setup a custom repository for your use with Ready Set Dice.

For creating creatures, you have two options:
- use an already existing tool, namely, https://monster.pf2.tools
- use Foundry Data formatting, see https://github.com/foundryvtt/pf2e for examples (packs/data/<name>-bestiary.db)

Using their JSON format, simple add the creatures to a repo like this and use the URL within Ready Set Dice.
Note, only you and your party will be able to use these creatures, unless you share the URL with others.

For this to properly work you need the following:
- Properly syntaxed JSON file(s) (see our examples)
- A version file with a number (increase it to update your creatures in RSD!)
- Add the username & repository name to your party settings (example: owner = ReadySetDice & gitname = rsd-custom-creatures)