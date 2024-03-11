# Automated Conditions 5e
![](https://img.shields.io/badge/Foundry-v11.315-informational) ![](https://img.shields.io/badge/Dnd5e-v3.0.4-informational) ![](https://img.shields.io/badge/AC5E-11.315.304.4.1-informational) ![GitHub Releases](https://img.shields.io/github/downloads/thatlonelybugbear/automated-conditions-5e/latest/total) ![GitHub Releases](https://img.shields.io/github/downloads/thatlonelybugbear/automated-conditions-5e/total) ![Forge Installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2Fautomated-conditions-5e&colorB=4aa94a) 


## For dnd5e v3.x, use manifest: 
<https://raw.githubusercontent.com/thatlonelybugbear/automated-conditions-5e/main/module.json>
## For dnd5e v2.x, use manifest: 
<https://raw.githubusercontent.com/thatlonelybugbear/automated-conditions-5e/dndv2/module.json>


## Description
A small module for Foundry and Dnd5e which uses dnd5e system Hooks to add the correct config options for Rolls, trying to automate the most common Dnd5e Conditions.

Rolling with Core, will indicate the correct button to press, on Attack Rolls, Damage Rolls, Saving Throws, Ability Checks and Skill Checks, according to the 5e ruleset.
Fast Forwarding the rolls (holding SHIFT) will roll with advantage/disadvantage or when needed critical damage correctly.

# Dnd5e Conditions supported
- **Blinded**: Disadvantage on attacks and grants advantage to attack from others
- **Exhaustion 1**: Disadvantage on ability checks (and skill checks as a result)
- **Exhaustion 2**: no changes
- **Exhaustion 3**: Disadvantage on attacks and saving throws
- **Exhaustion 4**: no changes
- **Exhaustion 5**: no changes
- **Frightened**: Disadvantage on ability checks and attack rolls; v10.0.3 will be testing for Visibility of origin if available to add this or not
- **Invisible**: Advantage on attacks and grants Disadvantage to attacks by others
- **Paralyzed**: Auto fail (-99) strength/dexterity saves and attacker within 5ft of the creature deals critical damage
- **Petrified**: Grants Advantage on attacks by others, auto fail strength/dexterity saves
- **Poisoned**: Disadvantage on attacks and ability checks
- **Prone**: Disadvantage on attacks, grants advantage on attacks by others if within 5ft, otherwise grants disdvantage
- **Restrained**: Disadvantage on attacks and dexterity saves, grants advantage on attacks by others
- **Stunned**: Auto fail strength/dexterity saves, grants advantage on attacks by others
- **Unconscious**: Auto fails strength/dexterity saves, grants advantage on attacks by others, crit if hit within 5ft ++ Prone

# Compatibility
Works with Core rolling, highlightning the correct buttons to press depending on the conditions on attacker and target, and Fast Forwards correctly.

# Credits
- Special thanks to [Zhell](https://github.com/krbz999) for using some of his code from [Babonus](https://github.com/krbz999/babonus).
