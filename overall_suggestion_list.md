I plan to break this large file up into more manageable pieces

All menus
- right-click outside of the menu box to close the current menu or back up to the previous menu

Options
- under documentation include illwiki.com and the mod inspector


Select Era
- allow clicking the description area to also select the relevant era
- a hotkey to change the (D)ifficulty of all the AI
- a hotkey to change the AI type (E)
- a hotkey to view the (m)ap and map description


Choose Participants, new game submenu
- typing a number adds that many players


Pretender Creation
- right-click on custom priest spells to see the spell description including ones that may be added by mods
- hotkey to view all possible holy spells (h)
- hotkey(x) to add repeats of the last bless added where legal, ex. undying


Game Settings, new game submenu
- change unique forging rate to accept a rate rather than limiting to 1 per turn and any number per turn
- change score graphs to enable each graph individually
- when setting the thrones allow the player to type the amount of each throne and the amount of throne points needed to win
- the save settings and load settings doesn't record whether random start research is on or off and it should
- an option to allow players to set the research from magic on the first turn


Network
- add ? hotkey to display the 'del' hotkey


Primary Game Screen/Strategic Map
- add Wait to the list of orders
- show the destination province number of commanders that are moving either next the command or when you hover the commander
- this one I am torn on whether it should be done or not: when you take a province( or scout with a unit that can see magic sites) and there is a site that has already been found via site searching show that the province has been searched with the values needed to find the site
- a hotkey to
  - toggle between hide all researchers, show only researchers, see all (alt-z)
	- the only new part of this one is the show only researchers
  - show only commanders that are moving (alt-v)
  - show only commanders equipped with items and/or gems (alt-q)
  - show only (alt-m)ages
  - show only (alt-p)riests
  - show only (alt-l)eaders
  - show only magic leadership (alt-g)
  - show only (alt-u)ndead leadership
  - show only the units set to (alt-d)efend and patrol, could consider combining this one with the researcher one
  - show only units (alt-c)casting rituals
  - show only units (alt-f)orging
- a tab structure similar to the hotkeys suggested could work too


Map filters
- add a filter to show only stealthed units and stealth movement (ctrl-s)
- fix the income box so it no longer hides the story event icon
- when income boxes are turned on include the pd in the top right corner of the box
- when income boxes are turned on include unrest beneath the pd
- create a new map filter and hotkey that hides armies and shows the players pd as troops on the map


Messages screen
- use tabs to separate the types of messages or a filter with hotkeys to filter or switch tabs
  - research and empower (1)
  - rituals cast and magic phase battles (2)
  - items forged(3): newly forged items should get messages similar to the rituals. "Commander X forged Y item in province Z
  - magic site searches (4)
    - after clicking on the message for sites found allow clicking or hovering over the site to see what it does
  - blood hunting and patrols (5)
    - this might be better organized by location as the primary criteria rather than show all the blood hunting then all the patrolling
  - battle phase battles and siege battles (6)
  - events, event battles, afflictions cured, new heroes, misc (7)
- on the battle summary screen do something to indicate pretenders, disciples, and prophets perhaps a symbol just before the count for each
	- a tag that can be given to commanders that will cause them to also be singled out in the battle summary for use by modders for various reasons
- a history of messages sent by other factions to player


Send Messages
- rename the title placard to something along the lines of 'Sending Messages'
- when sending magic items allow magic items to be selected until the player presses a done button at the bottom
- a history of message sent by player to other factions


F1 menu, Nation Overview

- on purely display and info
  - display the flag of the controlling nation before the province name
  - show the throne sprite before the province name in addition to showing the magic site emblem under sites
  - show the fort emblem under the site column with it clickable to see the fort details
  - add a recruitment point column and perhaps include commander recruitment points in parenthesis
  - the supplies and supplies used could be combined and displayed as a fraction; supplies used as the nominator and supplies as the denominator
  - adjust the position of the commanders commanding # units line so that a supplies-added by the commander can be placed in line with the supplies column
  - when the detailed menu(hotkey d) is activated allow the dominion candle to be clicked or hovered over to see the scales of the province if that info is available to the player
  - display which provinces that you have scouted with a colored background on the province name line, I think a light blue is appropriate
  - display provinces in which one of your forts is sieged with a colored background on the province name line, I think bright red is appropriate
  - display provinces in which you are besieging an enemy fort with a colored background on the province name line, maybe green not sure though
  - alternately to the 3 bullets above the text for the province name and number can be colored
  - show provinces that the player's partners control in disciples games and color code these as well
    - the provinces that the partners scouted should follow the scouting color scheme
  - a symbol to go in a commanders equipment section meant to state that the commander has gems

- on functionality
  - a sort by for each column that switches between highest and lowest
    - province number
    - province name
    - income
    - resources
    - recruitment points - also toggles between commander recruitment point amount
    - unrest
    - supplies - also toggle between used and total
    - province defense
    - sites - by the total number of sites maybe, not sure this one is all that useful
    - searches - toggle between the paths instead of by most and least similar to how the mod inspector sorts by paths
  - a sort by all commanders by their magic paths (toggling between paths) regardless of their location this could also be expanded into an entirely new menu
  - show the destination province number of commanders that are moving, either next to the command or when you hover the commander
  - allow each province to be individually collapsed to hide all the commanders at the location
    - add a hotkey to toggle collapsed and uncollapsed on all locations to (h)ide or unhide all the commanders

  - hotkeys for commander filters
    - toggle between hide all researchers, show only researchers, see all (alt-z)
    - show only commanders that are moving (alt-v)
    - show only commanders equipped with items and/or gems (alt-q)
    - show only (alt-m)ages
    - show only (alt-p)riests
    - show only (alt-l)eaders
    - show only magic leadership (alt-g)
    - show only (alt-u)ndead leadership
    - show only the units set to (alt-d)efend and patrol, could consider combining this one with the researcher one
    - show only units (alt-c)casting rituals
    - show only units (alt-f)orging

   - hotkeys for province filters
    - (F)orts under your control
    - (L)abs under your control
    - (T)emples under your control
    - provinces under your uncontested (C)ontrol

  - take you straight to the (r)ecruitment menu for the province that the mouse is hovering on
  - instead or maybe even in addition to the direct to recruitment menu hotkey add a hotkey to show recruitment at locations directly on the list and hide all units, this could potentially be an entirely new menu (R)


F2 menu, Scoregraphs
- allow zooming on any part of the graph
- put a slash through the flags of eliminated nations
- for disciples games have the disciple's flag be placed next to the pretender flag instead of the usual order and make the emblem for the disciple slightly smaller than pretender flags (or the pretender slightly larger)
- a hide all and show all hotkey or button next to the flags
- hotkey to filter for surviving nations


F3 menu, Hall of Fame
- nothing


F4 menu, Pretenders of the World
- get the nation info by clicking on the flag instead of the pretender name
  - hotkey to view only the national spells for the nation in the research menu (F5)
  - hotkey to view the national items for the nation (F6)
- in a disciples games add another column with the team number to make it easier to see the teams at a glance
- see the pretender and disciple stat of your own pretender and disciple here even when the unit isn't present on the map by right-clicking on the pretender name
- focus the map on a given pretender by left-clicking on it given their location is known
- one to think about, I am not solidly behind the idea: be able to see the base stats of previously scouted pretenders/disciples of other nations


F5 menu, Magic Research (also for Set battle orders where relevent)
- when viewing the spell list for a school add hotkeys to limit the view to UW castable spells and land castable spells
- add a hotkey to view the national spells of all the nations in the current game
- allow right-clicking construction 2, 4, 6, and 8 to view the magic items available at those levels, if not all at least the levels already researched
	- include the national items of all nations in the current game
- right-click on the rp left section to see the research cost per research-level chart for the current game, tag on a cumulative cost like the one here https://illwiki.com/dom5/research
- after clicking on a spell include the path requirements in the info I think at the top would be best but right above the fatigue cost would another good spot
- instead of just having cannot be cast underwater or only be cast underwater state can be cast: only UW, UW and on land, or only on land
- a little thing but think it would look nicer, instead of typing out gem required use "Gems required:" then follow with the number and the emblem for the gem type


F6 menu, Global Enchantments
- please please make the last slot more obvious when there is an even number of global slots, the last slot is easy to miss in situations like when there are 5 out of 6 globals up the last slot is just a bit of extra empty space before the exit button


F7 menu, Magic Resource Treasury aka the gem menu
- nothing


F8 menu, Magic Item Treasury
- unlimited size
- a hotkey to auto-sort by type
- color code unique items
  - if the item is also cursed split the color code along the diagonal
- allow the user to create tabs so that they can manually sort items to separate areas
- stack duplicate items


F9 menu, Thrones of Ascension
- if a player has discovered the province the throne is in display the province number and allow mouse click to focus the map on the province


Commander Stat Screen
- !!!allow cursed items to be unequipped the same turn it is equipped!!!
- allow existing hotkey 'l' to also transfer all gems to the lab when hovering the gem box
- allow items and gems to be swapped between units, ex only two units alone in a province without a lab both with magic helmets they should be able to swap
- allow renaming of commander by clicking on the name
- after clicking on morale display the home province beneath the upkeep
- after clicking on size display the supplies this unit consumes
- allow players to reorder the weapon attacks by dragging to dictate the order that the attacks are made in combat
- display upkeepp under morale in gold per month rather than gold per year


Army Setup menu
- see the siege strength of each commander and his troops next to the supply requirement
- see the patrol strength of each commander and his troops next to the supply requirement have this number be colored if the commander is currently set to patrol
- allow users to create tabs to manually move commanders to in order to help organize for various reason ex, put all comm slaves on a tab and all comm masters on another
- allow commander reordering through manual dragging
- add battle order target hotkeys for cavalry(H), fliers(F)
- allow selection of multiple commanders to assign orders in batches at the very least saved battle orders
- hotkeys for commander filters
  - toggle between hide all researchers, show only researchers, see all (alt-z)
  - show only commanders that are moving (alt-v)
  - show only commanders equipped with items and/or gems (alt-q)
  - show only (alt-m)ages
  - show only (alt-p)riests
  - show only (alt-l)eaders
  - show only magic leadership (alt-g)
  - show only (alt-u)ndead leadership
  - show only the units set to (alt-d)efend and patrol, could consider combining this one with the researcher one
  - show only units (alt-c)casting rituals
  - show only units (alt-f)orging
- a button(+) beneath the garrison to add another empty box to help sort the garrison, the new box would have button(-) to delete it, could also assign hotkey(+/-) for adding and deleting
- allow the hotkeys for formations to also work from the main army setup screen by using alt(ex. alt+l for a line formation) in front of them and hovering over the squads formation box to the right of there squad compoosition


Set battle orders for commander menu
- when clicking on line from the set battle orders open to the choose spell menu no matter whether it is a spell or not
- add a small button in front of each line that can be click-n-dragged to reorder the script
- allow the copy order, paste order, and view saved orders from this menu
- a check box at the bottom near conserve gems that tells the mages to enter range to cast any spells rather than cast something else

Saved Battle Orders menu
- more slots

Forge Magic Item menu
- color code unique items
- also color code cursed items red just like in the Magic Item Treasury menu (again split on diagonal if both)


Hire Mercenaries Menu
- show the troops commanded without clicking on them and the minimum bid for the player's nation
- place a hire button and a reset button for each mercenary on this screen
- each mercenary row would be: Company name, troops commanded, employer, min bid, bid, land, hire, reset
- just above the exit button state what % the nation the player is using adjusts for the mercenary price by


Recruitment menu
- beneath the existing troop recruitment display show a count of how many troops are being recruited to make it easier when recruiting large numbers
- hotkeys to
  - go to the next fort by province number (n)
  - go to the previous fort by province number (j)
  - go to the next province by number (N)
  - go to the previous province by number (J)
  - go to the next lab by province number (l)
  - go to the previosu lab by province number (p)


Province Defense
- beneath the existing troop display show a count of how many troops are there to make it easier with high PD values
- consider allowing scripting of pd commander and troops here
- consider allowing the commanders to be giving gems and magic items though like mercs don't allow them to be taken away unless it is the same turn they were given
- if scripting is permitted then supply a saved battle orders list specifically for PD?
- For a simpler option than a full script for pd perhaps a button that toggles between the pd being set to hold and attack and attack/fire
- Have and option to set an amount of resources that the province will hold onto perhaps make it permanant after the turn has passed just like pd cannot be decreased. Can also potentially limit it by requiring a certain amount of pd before allow this ability.


Battles
- allow the battle to be unpaused while viewing the Unit Overview and the battle log concerning specific units
- a slider to move back and forth in the timeline of the battle

New Menus
- empire-wide recruitment menu accessible from the strategic map also discussed under F1 menu (F10)

- an empire-wide commander listing that ignores location with sorting and filters also discussed under F1 menu (F11)
  - this menu would be to make finding commanders fitting certain criteria easier such as a commander to forge a specific item
  - left-clicking the commander would select the commander and focus the map on their provinces
  - right-clicking the commander would open the commander/stat menu for the commander
  - include the hotkeys already suggested in F1 menu for commander filters

- a notes menu, see Sword of the Stars 1 for inspiration
  - for the selected province see all notes and add notes, useable on the strategic map and F1 menu(ctrl-n)
    - if at least one note is present on the province    
      - see an asterisk in the top right corner in the red stripe of the province stat box on the strategic map
      - see an asterisk in the top right of the income box if that option is turned on while on the strategic map
      - see an asterisk next to the province name if the income box is turned off while on the strategic map
      - see an asterisk after the province number in the F1 menu
    - allow notes on never scouted provinces
  - add and see notes to commanders from their commander/stat menu
    - if at least one note is present on the commander
      - see an asterisk in the top right of his commander box while on the strategic map and the Army setup menu
      - see an asterisk after their name in the F1 menu and the empire-wide commander menu if implemented
  - allow notes on enemy heroes from via the hall of fame (ctrl-n) while hovering relevant area
  - allow notes on other nations via pretenders of the world and score graphs (ctrl-n) while hovering relevant area
  - allow notes on throne provinces via thrones of ascension (ctrl-n)
  - see all notes and add overarching notes with (shift-F1)
    - organize province notes by provinces
    - add the suggested F1 menu hotkeys for province filters
    - organize all commanders by province location
    - add the suggested F1 menu hotkeys for commander filters


Misc
- Twiceborn tag should say where the spell was cast

Choose Map, new game submenu
- nothing


Choose Map submenu, aka confirm or delete
- nothing


Continue Old Game
- nothing


View Pretenders
- nothing


Map Editor
- nothing without an overhaul


Random Map Creator
- nothing


Mod Preferences
- nothing


Preferences
- nothing
