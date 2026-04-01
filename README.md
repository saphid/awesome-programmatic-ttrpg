# awesome-programmatic-ttrpg

A curated list of open-source projects for building programmable tabletop RPG
software.

This list is for developers. It emphasizes reusable APIs, rules data, engines,
virtual tabletops, procedural generation, campaign tooling, and developer
libraries rather than general play aids.

GitHub metadata was checked live on April 1, 2026. Star counts below are only a
rough snapshot.

## Contents

- [Rules Data and APIs](#rules-data-and-apis)
- [Virtual Tabletops and Engines](#virtual-tabletops-and-engines)
- [Foundry Ecosystem for Developers](#foundry-ecosystem-for-developers)
- [Procedural Generation and Worldbuilding](#procedural-generation-and-worldbuilding)
- [Campaign, Character, and Authoring Tools](#campaign-character-and-authoring-tools)
- [Dice, Libraries, and Automation](#dice-libraries-and-automation)
- [Adjacent Awesome Lists and Resource Collections](#adjacent-awesome-lists-and-resource-collections)

## Rules Data and APIs

- [5e-bits/5e-srd-api](https://github.com/5e-bits/5e-srd-api) - REST API for
  the D&D 5e SRD. A strong starting point for builders of rules browsers,
  character tools, and VTT integrations. 602 stars.
- [open5e/open5e-api](https://github.com/open5e/open5e-api) - API backing
  Open5e. Useful if you want a broader open-content 5e data source. 195 stars.
- [open5e/open5e](https://github.com/open5e/open5e) - Open5e reference site and
  content hub for open 5e material. 428 stars.
- [rsek/dataforged](https://github.com/rsek/dataforged) - Ironsworn: Starforged
  rules and content in JSON, plus schemas and a JS/TS API. 214 stars.
- [rsek/datasworn](https://github.com/rsek/datasworn) - Successor project for
  Ironsworn and Starforged rules data in machine-friendly form. 148 stars.
- [farirpgs/fari-games](https://github.com/farirpgs/fari-games) - Open-content
  rules collection for multiple TTRPG systems. 35 stars.
- [openrpg/OpenRpg](https://github.com/openrpg/OpenRpg) - Core RPG-related data
  models and logic with an explicitly reusable focus. 87 stars.

## Virtual Tabletops and Engines

- [RPTools/maptool](https://github.com/RPTools/maptool) - Long-running virtual
  tabletop with a large installed base and a serious codebase. 894 stars.
- [vassalengine/vassal](https://github.com/vassalengine/vassal) - Open-source
  tabletop engine. Broader than TTRPGs, but important for engine builders. 576
  stars.
- [Kruptein/PlanarAlly](https://github.com/Kruptein/PlanarAlly) - Self-hosted
  VTT and battlemap platform. One of the better open VTT projects to study. 513
  stars.
- [farirpgs/fari-app](https://github.com/farirpgs/fari-app) - Free and
  open-source VTT with a lighter-weight, more modern web stack. 317 stars.
- [samcf/ogres](https://github.com/samcf/ogres) - Minimal browser-based VTT
  with a nice no-nonsense scope. 166 stars.
- [curtmorgan3/quest-bound](https://github.com/curtmorgan3/quest-bound) - Free
  and open-source tabletop game engine. Younger project, but clearly aligned
  with the programmable-tooling angle. 25 stars.
- [fjallnari/morii-vtt](https://github.com/fjallnari/morii-vtt) - Web-based
  half-VTT supporting 5E, Cairn, and Shadowdark. 18 stars.

## Foundry Ecosystem for Developers

- [foundryvtt/dnd5e](https://github.com/foundryvtt/dnd5e) - Official open 5e
  system implementation for Foundry VTT. Great reference code for system
  authors. 511 stars.
- [foundryvtt/pf2e](https://github.com/foundryvtt/pf2e) - Community Pathfinder
  2e system for Foundry. One of the strongest open TTRPG codebases on GitHub.
  586 stars.
- [foundryvtt-starfinder/foundryvtt-starfinder](https://github.com/foundryvtt-starfinder/foundryvtt-starfinder)
  - Community Starfinder system for Foundry. 97 stars.
- [fvtt-fria-ligan/forbidden-lands-foundry-vtt](https://github.com/fvtt-fria-ligan/forbidden-lands-foundry-vtt)
  - Forbidden Lands system for Foundry. 203 stars.
- [League-of-Foundry-Developers/foundry-vtt-types](https://github.com/League-of-Foundry-Developers/foundry-vtt-types)
  - Unofficial TypeScript declarations for the Foundry API. Essential for typed
  module and system work. 147 stars.
- [League-of-Foundry-Developers/FoundryVTT-Module-Template](https://github.com/League-of-Foundry-Developers/FoundryVTT-Module-Template)
  - Module starter with CI/CD and versioning conventions. 167 stars.
- [ghost-fvtt/foundry-factory](https://github.com/ghost-fvtt/foundry-factory) -
  CLI bootstrapper for new Foundry modules and systems. 44 stars.
- [foundry-vtt-community/macros](https://github.com/foundry-vtt-community/macros)
  - Community macro collection. Useful as both examples and drop-in building
  blocks. 226 stars.
- [foundry-vtt-community/tables](https://github.com/foundry-vtt-community/tables)
  - Community roll tables for Foundry. 52 stars.
- [kgar/foundry-vtt-tidy-5e-sheets](https://github.com/kgar/foundry-vtt-tidy-5e-sheets)
  - Clean 5e sheet layouts for Foundry. Good UI-focused reference. 75 stars.
- [vigoren/foundryvtt-simple-calendar](https://github.com/vigoren/foundryvtt-simple-calendar)
  - Calendar and timekeeping module. 70 stars.
- [fantasycalendar/FoundryVTT-Sequencer](https://github.com/fantasycalendar/FoundryVTT-Sequencer)
  - Effect sequencing pipeline for Foundry modules. 69 stars.
- [ruipin/fvtt-lib-wrapper](https://github.com/ruipin/fvtt-lib-wrapper) -
  Foundry library for patching and wrapping core behavior with less conflict. 43
  stars.
- [Ethaks/FVTT-Quench](https://github.com/Ethaks/FVTT-Quench) - End-to-end UI
  testing inside Foundry. 32 stars.
- [dev7355608/perfect-vision](https://github.com/dev7355608/perfect-vision) -
  Lighting and vision extension module with technically interesting rendering
  work. 52 stars.

## Procedural Generation and Worldbuilding

- [Azgaar/Fantasy-Map-Generator](https://github.com/Azgaar/Fantasy-Map-Generator)
  - Heavyweight fantasy world and map generator with excellent output and deep
  customization. 5,567 stars.
- [ryceg/Eigengrau-s-Essential-Establishment-Generator](https://github.com/ryceg/Eigengrau-s-Essential-Establishment-Generator)
  - Play-ready town and establishment generator for fantasy campaigns. 873
  stars.
- [halftheopposite/bsp-dungeon-generator](https://github.com/halftheopposite/bsp-dungeon-generator)
  - Configurable BSP-based dungeon generator. Nice algorithmic reference. 123
  stars.
- [Mimic-Tools/name-generation](https://github.com/Mimic-Tools/name-generation)
  - Fantasy character name generation tooling. 19 stars.
- [McAJBen/DungeonBoard](https://github.com/McAJBen/DungeonBoard) - Spoiler-safe
  map viewer for DMs. 60 stars.
- [schemen/monsterforge](https://github.com/schemen/monsterforge) - Paper
  miniature creator. 29 stars.

## Campaign, Character, and Authoring Tools

- [ebullient/ttrpg-convert-cli](https://github.com/ebullient/ttrpg-convert-cli)
  - Convert owned JSON data from 5etools or pf2etools into Obsidian-friendly
  Markdown. Excellent bridge between structured content and campaign docs. 348
  stars.
- [carlonicora/obsidian-rpg-manager](https://github.com/carlonicora/obsidian-rpg-manager)
  - Campaign management plugin for Obsidian. 223 stars.
- [Obsidian-TTRPG-Community/initiative-tracker](https://github.com/Obsidian-TTRPG-Community/initiative-tracker)
  - Initiative tracker for Obsidian-based campaigns. 193 stars.
- [iron-vault-plugin/iron-vault](https://github.com/iron-vault-plugin/iron-vault)
  - Obsidian plugin for Ironsworn and Starforged play. 97 stars.
- [PCGen/pcgen](https://github.com/PCGen/pcgen) - Long-running character
  generation and play-assist project. 461 stars.
- [wanderers-guide/wanderers-guide](https://github.com/wanderers-guide/wanderers-guide)
  - Pathfinder and Starfinder character builder and toolbox. 28 stars.
- [ebshimizu/5e-monster-maker](https://github.com/ebshimizu/5e-monster-maker) -
  Monster stat block builder for 5e. 46 stars.
- [brouberol/5esheets](https://github.com/brouberol/5esheets) - Browser-based
  5e character sheet tooling. 31 stars.
- [derikb/character-sheet-app](https://github.com/derikb/character-sheet-app) -
  Offline-capable web character sheet app for 5e and other RPGs. 98 stars.
- [GoOz/wfrp-sheet](https://github.com/GoOz/wfrp-sheet) - Online character sheet
  for Warhammer Fantasy Role Play. 27 stars.
- [fultimator/fultimator](https://github.com/fultimator/fultimator) - Homebrew
  creator for Fabula Ultima adversaries, items, and characters. 28 stars.
- [scottbenton/Iron-Fellowship_and_Crew-Link](https://github.com/scottbenton/Iron-Fellowship_and_Crew-Link)
  - Shared-play character and campaign tools for Ironsworn and Starforged. 32
  stars.
- [BigJk/snd](https://github.com/BigJk/snd) - Sales and Dungeons, a thermal
  printer utility for D&D and TTRPG play. Weird, specific, and fun. 610 stars.

## Dice, Libraries, and Automation

- [ianfhunter/GNOLL](https://github.com/ianfhunter/GNOLL) - Multi-language dice
  notation parser with broad notation support. 48 stars.
- [Roll20/roll20-api-scripts](https://github.com/Roll20/roll20-api-scripts) -
  Canonical Roll20 API script collection maintained by the ecosystem. 403 stars.
- [shdwjk/Roll20API](https://github.com/shdwjk/Roll20API) - Production-ready
  Roll20 API scripts and utilities. 85 stars.
- [apocabot/ApocaBot](https://github.com/apocabot/ApocaBot) - Discord bot for
  Powered by the Apocalypse games. 37 stars.
- [rpg-sage-creative/rpg-sage](https://github.com/rpg-sage-creative/rpg-sage) -
  Discord bot for play-by-post TTRPG gaming. 16 stars.

## Adjacent Awesome Lists and Resource Collections

- [5e-bits/awesome-5e-srd](https://github.com/5e-bits/awesome-5e-srd) -
  Existing awesome list for projects built on the 5e SRD API. 74 stars.
- [Billiam/awesome-ironsworn](https://github.com/Billiam/awesome-ironsworn) -
  Strong ecosystem list for Ironsworn and Starforged projects. 180 stars.
- [bryancasler/Bryans-Preferred-Modules-for-FoundryVTT](https://github.com/bryancasler/Bryans-Preferred-Modules-for-FoundryVTT)
  - Curated module stack for Foundry users. More user-facing than developer
  tooling, but still useful for ecosystem discovery. 137 stars.

## Contribution Guide

Pull requests are welcome if the repository:

- is publicly accessible on GitHub
- is directly useful to developers building TTRPG software
- has enough substance to be more than a throwaway demo
- fits one of the sections above

When adding entries, prefer a short, concrete explanation of why a builder
should care.
