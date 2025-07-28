# Save Editors
An archive of HTML/JavaScript-based editors I have made for various games. They are in a variety of states of completeness but all should be functional for the options they do present. Each editor also comes with a sample file.

All these editors are designed as a single file for ease of portability.

**Always backup your save files before editing them.**  
While I have made every effort to ensure that the edited files that result are valid save files that does not mean that the game will perform as expected in all situations e.g. giving yourself a key item earlier than would normally be possible.  
I accept no responsibility if you lose progress as a result of using any of these editors.

## Framework
This is the core code of the editor stripped of any game specific logic.  
Used as a base for any new projects but not guaranteed to applicable to any older projects without significant work.

## Final Fantasy XIII
### [Download (right-click --> Save link as…)](https://raw.githubusercontent.com/BtEtta/save-editors/refs/heads/main/ffxiii/ffxiii.html)
**Licenced under GPL 3.0**  
Supports editing saves from the Windows port of Final Fantasy XIII  
* Party, and associated paradigms  
* Individual character stats  
* Inventory editing for all inventories (Items, Weapons, Accessories, Components, and Key Items)  
* Datalog completion including enemy intel
* Supports both encrypted saves, and saves decrypted using an external tool (the game will only load encrypted saves).
This editor uses code derived from https://github.com/Surihix/WhiteCryptTool to handle file encryption.

## Hyrule Warriors: Age of Calamity
### [Download (right-click --> Save link as…)](https://raw.githubusercontent.com/BtEtta/save-editors/refs/heads/main/aoc/aoc.html)
* Complete as regards editing materials collected and their quantities.  
* Weapon editor is fully functional but more research is needed around EXP caps for different weapon types and default subvalues for seals.  
* No work has begun on the character editor.

## Ikenfell
### [Download (right-click --> Save link as…)](https://raw.githubusercontent.com/BtEtta/save-editors/refs/heads/main/ikenfell/ikenfell.html)
* Edit party status including level, exp, and equipped items.  
* Full inventory editing.  
* Attempts to avoid spoilers by default.  
* Includes an advanced mode (with no spoiler protection) that displays all values in the save in a raw format. You can also edit the games settings file in this mode.

## Shenmue I & Shenmue II HD
### [Download – Shenmue I (right-click --> Save link as…)](https://raw.githubusercontent.com/BtEtta/save-editors/refs/heads/main/shenmue-hd/shenmue.html)
### [Download – Shenmue II (right-click --> Save link as…)](https://raw.githubusercontent.com/BtEtta/save-editors/refs/heads/main/shenmue-hd/shenmue2.html)
* Changing the in-game date & time.  
* Full editing of the inventories, including side content such as capsule toys.  
* Full editing of your available moves, and their levels.  
* Full editing of arcade machine high scores. Which will trigger the correct cutscenes when certain thresholds have been met.  
In theory these editors should also work for the original Dreamcast releases provided you can handle the VMU checksums and encapsulation. This is untested.

## Trials of Mana/Seiken Densetsu 3
### [Download (right-click --> Save link as…)](https://raw.githubusercontent.com/BtEtta/save-editors/refs/heads/main/trials/trials.html)
This is the oldest of the editors I have made and lacks some of the polish of later editors.  
* Allows for full inventory editing & full editing of stats for your three characters (although several of those stats are recalculated by the game in various circumstances)  
* Name editing should work for the English 2018 re-release, the 2000 Neill Corlett fan translation, and the original Japanese release.  
Labels for items and other in-game text should also match for the two English translations but would need someone capable of reading and inputting Japanese for the labels to be correct for that version.

## Notes
### Debug Mode
Many of these editors will have a debug mode. Enabling this will change the behaviour of certain pieces of code and may reveal extra viewing/editing options used during development.  
This should not be required unless you have a curious mind or you're planning on extending the available features of the editor.

In the newest versions of the framework this can be enabled by adding `?debug` to the end of the URI in the address bar.

Older files may instead contain a line similar to the following which can be changed to any truthy value in JavaScript to enable:
```
const debug = 0;
```

## Licence
The Framework and all editors have the following licence unless otherwise noted.

Copyright (c) 2025 Robin Zalek

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.