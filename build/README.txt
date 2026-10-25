AS THEY SAW IT
Prototype build - GDS6 Final Milestone
Written & designed by Tanaka Simonsen (titikormetsi studios)

------------------------------------------------------------
CONTENT NOTE
------------------------------------------------------------
This game deals with alcohol addiction, recovery and mental health.
It includes references to suicidal ideation, grief, sexual abuse and
cultural genocide, and strong language.

If any of this brings something up for you:
  Lifeline (Australia): 13 11 14
  National Alcohol and Other Drug Hotline (Australia): 1800 250 015
  Alcoholics Anonymous Australia: aa.org.au

------------------------------------------------------------
HOW TO RUN (WINDOWS)
------------------------------------------------------------
1. Unzip the WHOLE folder. Keep these together, side by side:
     As-They-Saw-It.html
     assets\   (fonts and UI images)
     audio\    (sound effects)
   The game will lose its fonts, UI art and sound if the HTML is
   moved out of this folder.
2. Double-click As-They-Saw-It.html. It opens in your web browser
   (Chrome or Edge recommended).
3. An internet connection is recommended: character sprites and the
   body font (VT323) load online. Without internet the game still
   plays, but portraits will be blank.
4. Best viewed fullscreen (press F11) at 1920x1080, with sound on.

1 player. Mouse and keyboard. No gamepad support.

------------------------------------------------------------
CONTROLS
------------------------------------------------------------
Click the arrow (▼) or press SPACE ... continue to the next line
TAB ............................... cycle through typed reply options
ENTER ............................. send the selected typed reply
Any letter key .................... when a line appears with a
                                    blinking cursor, type to write out
                                    the Higher Power's words
"(push further)" / "(press further)"  click to dig deeper into a nudge
Clickable lines in a speech bubble  make a choice
"skip ▶▶" ......................... skip a long meeting share
⏩ button (bottom right) ........... fast mode, text appears instantly

Sidebar (left):
  Arrows ............ step back / forward through passages
  SAVES ............. save and load your game
  RESTART ........... start again from the beginning
  MEMORY BANK ....... what you have learned about each character,
                      plus quotes you have collected
  ACHIEVEMENTS ...... moments you have found

------------------------------------------------------------
HOW TO PLAY
------------------------------------------------------------
You are a higher power - a quiet presence sitting in on the weekly
Mirabel AA meeting. At the end of the meeting, look around the circle
and choose someone to follow home for the week.

You can hear their thoughts and drop small nudges, but you cannot
control them. There is no right answer and no score that "fixes"
anyone. What you say, and when you push or hold back, changes how
open or guarded they become, and that shapes how their week ends.

This prototype contains:
  Book 1 - Anesu Song's week (multiple branches and endings)
  Book 2 - Erin Ferguson's first chapter (unlocks after Book 1)
Other meeting members are shown but locked.

Play again to find the other endings - the end screen shows how many
you have found.

------------------------------------------------------------
KNOWN ISSUES
------------------------------------------------------------
- Character portraits are hosted online and will not show without an
  internet connection.
- Refreshing the browser keeps your current progress. Use RESTART in
  the sidebar for a fresh start.
- On screens smaller than 1920x1080, sidebar buttons and the credit
  text can appear cut off.
- Choosing Anesu a second time from the end-of-week member list can
  show a small error; the game continues normally.
- Member stories for locked characters are placeholders ("Coming
  soon...") as they are not part of this prototype.
- You may need to scroll if you don't see any links or buttons

------------------------------------------------------------
STARTING FRESH / RESETTING ACHIEVEMENTS
------------------------------------------------------------
Achievements, saves and the Memory Bank are remembered by your
browser, not the game file. If you have played an earlier copy
on this computer, they may already show as unlocked.

To reset everything:
1. Open the game.
2. Press F12 and click the "Console" tab.
3. Paste the line below and press Enter:

   localStorage.clear(); sessionStorage.clear(); location.reload();

Or open the game in a private window (Ctrl+Shift+N in Chrome,
Ctrl+Shift+P in Edge) for a clean playthrough every time.

------------------------------------------------------------
CREDITS AND EXTERNAL ASSETS
------------------------------------------------------------
Writing, narrative design and programming: Tanaka Simonsen
Art: [FILL IN - confirm artist credit]

Engine: Twine / SugarCube 2.37.3 by Thomas Michael Edwards
        https://www.motoslave.net/sugarcube/2/
Built with Tweego and Visual Studio Code.

FONTS
Font            | Used for                       | Designer      | Source                                          | Licence

VT323           | Body text                      | Peter Hull    | https://fonts.google.com/specimen/VT323         | SIL Open Font License 1.1
Pixelta         | Menus, headings                | Blankids Studio | https://www.dafont.com/pixelta.font           | PERSONAL USE ONLY and NO COMMERCIAL USE ALLOWED 
cozy-quill      | Opening monologue, title screen| DeerEyes      | https://www.dafont.com/cozy-quill.font          | N/A
Reindeer Modern | Higher Power, name box         | DeerEyes      | https://www.dafont.com/reindeer-modern.font     | N/A
Northern Sans   | Anesu's dialogue               | Matthew Flanegan | https://www.dafont.com/northernsans.font     | N/A
Wyvern          | Mama's dialogue                | jsr_Games     | https://www.dafont.com/wyvern.font              | N/A
Dico            | Dad's dialogue                 | Yannic Kotter | https://www.dafont.com/dico.font                | N/A
ZX Spectrum-7   | Micah's dialogue               | Style-7       | https://www.dafont.com/zx-spectrum-7.font       | N/A
Game Font       | Erin's dialogue                | Sean Denny    | https://www.dafont.com/game-2.font              | FREE FOR ANY USE, COMMERCIAL OR PRIVATE
Smalle          | Drunk Erin                     | memesbruh03   | https://www.dafont.com/smalle.font              | N/A
Grape Soda      | Thought bubbles                | jeti          | https://www.dafont.com/grapesoda-2.font         | FREE TO USE THIS FONT FOR PERSONAL OR COMMERICAL PROJECTS
Levi Windows    | Stage directions, typing hint  | Levi Szekeres | https://www.dafont.com/leviwindows.font         | N/A
Pokemon X and Y | Narrative box                  | TheLouster11  | https://www.dafont.com/pokemon-x-and-y.font     | N/A
dogica          | Sidebar status                 | Roberto Mocci | https://www.dafont.com/dogica.font              | FREE FOR PERSONAL USE AND COMMERCIAL. OFL.

OTHER CHARACTERS
Julian, the stray cat
https://carysaurus.itch.io/siamese-cat-sprites

AUDIO
Blips & beeps (character voices): dmochas-assets, itch.io
  https://dmochas-assets.itch.io/dmochas-bleeps-pack

Sound effects: Epidemic Sound [FILL IN - licensed via subscription?]
  https://www.epidemicsound.com/sound-effects/tracks/ae404061-b81d-4d28-a4ce-5038d769590f/
  https://www.epidemicsound.com/sound-effects/tracks/6e5e8a21-7ae5-411c-8c07-c01a5b963efc/
  https://www.epidemicsound.com/sound-effects/tracks/7227071f-784c-4d50-9587-851b3ce15783/
  https://www.epidemicsound.com/sound-effects/tracks/6ab0e5d1-9251-4a6a-9445-0c765d8d0987/
  https://www.epidemicsound.com/sound-effects/tracks/03636a45-d3a2-4752-82d5-79e630116058/
  https://www.epidemicsound.com/sound-effects/tracks/831ecf2f-2b97-49f9-a38d-4fcd2124fa55/
  https://www.epidemicsound.com/sound-effects/tracks/a45c1f36-ad75-4770-96db-aacccd708f24/

Quotes and sentiments from Alcoholics Anonymous literature
(the Big Book) and the Serenity Prayer are used in the meeting scenes.