# Save Editors
An archive of HTML/JavaScript-based editors I have made for various games. They are in a variety of states of completeness but all should be functional for the options they do present. Each editor also comes with a sample file.

All these editors are designed as a single file for ease of portability.

**Always backup your save files before editing them.** While I have made every effort to ensure that the edited files that result are valid save files that does not mean that the game will perform as expected in all situations e.g. giving yourself a key item earlier than would normally be possible.
I accept no responsibility if you lose progress as a result of using any of these editors.

## Hyrule Warriors: Age of Calamity
Complete as regards editing materials collected and their quantities.
Weapon editor is fully functional but more research is needed around EXP caps and default subvalues for seals.
No work has begun on the character editor.

## Trials of Mana/Seiken Densetsu 3
This is the oldest of the editors I have made and lacks some of the polish of later editors.
Name editing should work for the English 2018 re-release, the 2000 Neill Corlett fan translation, and the original Japanese release. Labels for items and other in-game text should also match for the two English translations but would need someone capable of reading and inputting Japanese for the labels to be correct for that version.

## Notes
Several of these files will contain a line similar to the following:
```
const debug = 0;
```
Setting this value to 1 will change certain behaviours within the editor, exposing more options or changing how existing ones are displayed. This should not be required unless you're planning on extending the available features of the editor.

## Licence
Copyright (c) 2024 Robin Zalek

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