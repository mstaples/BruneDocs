CHANGELOG for 0.4.4
===================

0.4.4.2

* (2014-3-6)

 * add death and fatigue handling to combat
 * add notification on interception combat to both parties
 * add contribute to scenario on successful interception combat
 * add formation and position handling for interception combat
 * fix combat report: attacker army names
 * add combat report: color border indicating damage
 * add combat report: damage by position by combat round

* (2014-3-5)

 * fix bugs w fight vs. character damage
 * fix bugs w fight vs. character army positions
 * add combat report: attacker / defender images
 * add take prisoner on successful combat when appropriate
 * add combat report: army positions facing
 * add combat report: deserters
 * add equipment effects to army current attrib calc
 * add combat report: wide / centered layouts
 * add combat report: deaths
 * add combat report: attacker / defender tactics flags
 * add combat report: unit image to position display
 * add combat report: unit name, count to position title
 * add combat report: consolidate identical damage messages
 * add combat report: damage data by round
 * add combat report: by round army position display
 * add create report from combat records

* (2014-3-4)

 * add max rounds to combats by attacker rank
 * fix bugs with combat rounds count
 * add attribute to inflict damage bonus passing
 * add can wield magic, ranged, artillery check types for armies
 * add combat position records by round activity
 * add formation and position handling to fight vs. character
 * add fatigue and deserter handling to combat rounds
 * add determine unit combat damage access by class, equipment, and position
 * add create personal notice on combat creation
 * add jump to combat report from combat creation
 * add disband transportation unit option in Manage->Shipping

* (2014-3-3)

 * add combat unit count records by round
 * add distribute combat round damage to army by position
 * add combat deaths, damage, and deserters records by round
 * add combat message records by round activity
 * add by type damage / resistance calc to combat
 * add character when present to current army attrib calc
 * add equipment effects to current army attrib calc
 * add tactical bonuses to current army attrib calc
 * add calc current army attributes per combat round
 * add remove forum interaction from fight vs. character
 * add remove placeholder formations and tactics data from fight vs. character
 * add update to award badges
 * add combat damage distinctions for melee, ranged, artillery, and magic types

* (2014-3-2)

 * add calc per unit position and tactics effects based on combat tactics outcome
 * add tactics and positions bonuses fixture / command / records

* (2014-3-1)

 * add combat position selection for character
 * add update fight vs. NPC to use current army records
 * add alter army positions based on tactics outcome
 * add determine tactics outcome at initiate combat
 * add NPC troop records for vs. NPC combats
 * add remove forum interaction from combats
 * add per combat round formation records
 * add per combat tactics records
 * add separate position storage per combat from orders
 * add troop type handling to formation orders
 * add displace previously placed unit in position selection

* (2014-2-28)

 * fix bugs with Recruit district placement
 * fix bugs with do Recruit

* (2014-2-27)

 * add abandoned timer of two weeks to personal interactions
 * add tactics info to selection
 * add unit info to position image caption
 * add selected tactic flag to manage gear pages
 * add tactics selection option to Manage->Gear

* (2014-2-26)

 * fix Downgrade setting employment to zero
 * add Minister management of transportation units in their district
 * add unit images and titles to position selection
 * add placed units to position selection view
 * add row labels to troop position selection
 * add position selection option to manage army unit
 * add flag to forum author info
 * fix bug w badge display on forum posts
 * add flag component access update to character creation
 * add catch to prevent premature upkeep repetitions

0.4.4.1

* (2014-2-25)

 * fix hire garrison bugs
 * fix fire garrison bugs
 * add symbol access limit based on rank calc
 * fix http / https mismatch error
 * fix hero rank error
 * fix flag display on report pages
 * add update flag header image on change save
 * add update flag name on change save
 * add change flag use from png to svg

* (2014-2-24)

 * fix flag image load to editor on test
 * add flag to character report pages
 * add flag editor access on header flag select
 * add flag or flag icon display to character header
 * add remove inapplicable color tools from editor ui
 * fix palette size to expand / contract with available color count
 * add remove inapplicable editor main menu items
 * add "Save Flag" instead of "Save Image" to main menu
 * add limit flag canvas size to prevent internal scrolling
 * add fetch flag color access based on current session character records
 * add audit component access command to grant basic flag symbol and color access
 * add build symbol libraries in editor based on fetched access array
 * add fetch flag symbol access based on current session character records
 * add remove old session records when creating new
 * add audit symbol access command to grant basic level / rank / char creation based symbol access

* (2014-2-23)

 * add error output on processing events
 * add reduced output on storage decay events
 * add reduced output on Immigration events
 * add waiting spinner on select loads > 1.5 seconds
 * fix bug with Restore Wear timer event
 * fix bug with Restore Fatigue timer event

* (2014-2-22)

 * add waiting spinner to speed construction popup
 * add size constraints to speed construction popup to prevent jumping
 * fix Stocks & Pillory buttons in catalog
 * fix Vinyard to Vineyard in catalog
 * add additional decimal display on scenario contribution totals
 * fix bug w global scenario submissions
 * fix bug w global scenario access
 * add select pointer tool on reaching check limit
 * add remove ui components to add new flag items on reaching check limit
 * add check current item use on canvas select

* (2014-2-21)

 * remove inapplicable editor shape options from menus
 * add fetch flag component limit from game by session character
 * add more secure session info passing between game and editor
 * add correct permissions when new flags created
 * add save png version at flag save using Imagick
 * add static flag size / shape to editor
 * add load editor content by save name only (no cache saving)
 * add name saved flags based on character session
 * add retrieve flags based on character session

* (2014-2-20)

 * remove unnecessary editor ui components
 * add save flags locally to server
 * add editor call to game for session player info for flag naming
 * add php_savefile extension to editor
 * update svg editor version
 * add check for existing flag on editor load based on player session
 * add svg editor access path

0.4.4.0

* (2014-2-19)

 * add spinner to loading segments
 * add improved speed in level up calc
 * fix progress bar on targeted actions
 * fix repeat on targeted actions
 * add increase repetition and rank timers to actions progress bar
 * add improved non-targeted action performance
 * add improved settlement page loading

* (2014-2-18)

 * add improved actions overview loading
 * add improved best xp and importance action calc
