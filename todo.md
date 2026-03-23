# To Do

## To Do List

[] Plan features and requirements
[] Write pseudocode logic
[] Make json "tables"
[] Write logic
[] Build a front-end? Or a nice TUI.

## Requirements/features

I want to be able to:

- set a date as the prompt for the notes that'll auto add the first time I take a note on that date, and that can advance with a particular command (or set to a new date)
- Type in a string of thoughts or a bang followed by thoughts and it'll add that string to a session notes doc.
- Have ongoing treasure counter that I can add to with a d. value and then description (e.g. `treasure add 500 diamond`), that when I say like `treasure distribute 6 1` it'll distribute it six ways with one retainer, and give me XP values for each.
- Randomly roll up an NPC, have it spit out the NPC's name & characteristics, give me the option to add a note, and add it to my session notes and also an NPC list, depending on whether it's a campaign-only NPC or world NPC.
- NPC list that opens with a command (gonna be just easier to search a file in nvim, unless I somehow set up fuzzy find to say the character's name and have its data pop up)
- Make a level 1 character generator (for use mainly for NPCs & retainers)
- Feats of exploration auto calculator - let me set up a group keyword like dolmenwood or globetrotters and store the party's characters and levels and it'll tell me how much xp each character gets when I say like `feat dolmenwood`.
- Level-up bullet point checklist that auto increases the character's levels. Like `level dolmenwood` and it shows the list of characters and asks me which level up. And i can say 1,2,4 for characters 1 2 and 4 and it'll show me the checklist and auto increase those characters' levels in my database.
- a neat combat cheat-sheet spread with the info right there that I need, like what's on my cheat sheet
- random encounter roll tables - input both Dolmenwood and regular, though I need to decide which I'll use for that
- treasure roll tables (use Dolmenwood's)
- carousing complication input table (don't auto roll, but I'll tell you the player's roll and you tell me the outcome)
- Look up an item's default price, or preceed it with a city name to get a custom price and availability, though this'll be really annoying to do - I'll need to decide on a single source of truth for this data
- speculative trade auto-roller & calculator (check back page of blue folder for categories plus speculative trade section of hartrpg.com)
- maybe even a "shop" command that's searchable with auto-complete ... like start typing "torch" and it'll have the options underneath, and then type an integer for how many they're buying and hit enter and it'll add to a running total of stuff that I can remove a line from if they change their mind, and it'll show the total at the top.
