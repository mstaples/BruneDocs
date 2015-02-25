CHANGELOG for 0.4.4
===================

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
