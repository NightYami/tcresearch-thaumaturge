# Thaumaturge Research Helper

A small web tool that finds the shortest chain of aspects between two aspects on a research note in
[Thaumaturge](https://github.com/Leclowndu93150/Thaumaturge) (NeoForge 26.1.2, as used in All the Mods 11).

Based on the **[Thaumcraft Research Helper](https://github.com/ythri/tcresearch) by ythri** (CC BY 4.0).
This copy replaces the Thaumcraft 4/5 aspect tables with Thaumaturge's 37 aspects (6 primals + 31 compounds).

## Using
Choose **From** and **To** aspects from your research note and the minimum number of steps between them,
then click **Find Connection**. Disable aspects you do not have yet under *Available Aspects* and the tool
will route around them where it can.

## Data
`version_dictionary.js` lists each compound aspect as the two aspects it is made from, read from Thaumaturge's
aspect registry (`AspectBootstrap`). `translation_dictionary.js` maps aspect names to icon files and plain-English labels.
Addon aspects can be added in `addon_dictionary.js`.

## Licence and credits
- Original tool: ythri, [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/). Modified here.
- Aspect combinations are facts about the Thaumaturge mod (Leclowndu93150 and contributors). No Thaumaturge code or art is included.
- The `alkimia` icon is a placeholder drawn for this project.
- `vendor/` contains jQuery 1.7.2 and jQuery UI 1.10.4 (MIT licence, jquery.org), included so the page loads nothing from third-party servers.
