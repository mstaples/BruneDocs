   CHANGELOG for 0.7.14
   ===================

   0.7.14.3

   * (2015-9-19)

    * add api get achievements route
    * add get next skill achievement
    * add get next secret achievement
    * add get next level achievement
    * add get next rank achievement
    * add get next trait achievement
    * add get next class achievement
    * add settlement achievements report
    * add character achievements report

   * (2015-9-18)

    * add award new achievement
    * add check character achievements on character select
    * add check settlement achievements on sovereign select
    * add search achievements for edit
    * add edit achievements by missing steam id
    * add edit achievements by missing steam num
    * add edit achievements by missing description
    * add edit achievements by missing image
    * add edit achievement form

   * (2015-9-17)

    * add achievement notice to skill level up
    * add achievement notice to rank up
    * add achievement notice to % 50 levels
    * add import achievements command
    * add cede acres history output to ui
    * add cede acres record keeping by donation target

   * (2015-9-16)

    * add images to cede acres award output
    * add updated cede acres award content
    * add updated cede acres award chances
    * fix form fragment container

   * (2015-9-15)

    * update cede acres admin output
    * add new cede acre tier chances
    * add import cede acres command
    * update test voting command

   * (2015-9-09)

    * fix landing page login buttons

   * (2015-9-08)

    * fix landing page js
    * add forum default layout to wide
    * add redeemed time to premium purchase record
    * add make logged character optional for premium purchase
    * add integrate purchase premium form messaging
    * add purchase premium page
    * add purchase premium form
    * add skip character selection option if missing records
    * add "Not a populated region" message for targeting where appropriate
    * ts wiki db credentials
    * add fav icon to landing page
    * fix bug w main page load

   * (2015-9-07)

    * fix bugs w tutorials
    * fix character creation flow
    * add indiedb graphic client download to landing page
    * add support to landing page
    * add forums to landing page
    * add wiki to landing page
    * add new landing page layout

   0.7.14.2

   * (2015-9-07)

    * add Sell Transportation Unit: rented slot messaging
    * add Sell Transportation Unit: slot shortage messaging
    * add Sell Transportation Unit: Sale fails if no qualifying slots available
    * add Sell Transportation Unit: Remove crew on sale
    * add Sell Transportation Unit: Transfer Slot ownership on transport sale

   * (2015-9-06)

    * add Transportation Slot Management: Recruit building shut down based on slot availability
    * add Transportation Slot Management: Slot based location on transport recruit
    * add Transportation Slot Management: Relocate or destroy unhoused transport
    * add Transportation Slot Management: Increase transport slots on building upgrade
    * add Transportation Slot Management: Decrease transport slots on building downgrade
    * add Transportation Slot Management: Create transport slot record on building creation
    * add Transportation Slot Management: Relocate or destroy transport on disqualifying setting change
    * add Transportation Slot Management: Notify storage users on setting change
    * add Transportation Slot Management: Rent "For Rent" storage spots
    * add Transportation Slot Management: Change Transport Storage Building
    * add Transportation Slot Management: Update storage users on rent change
    * add Transportation Slot Management: Change "For Rent" Slot Price
    * add Transportation Slot Management: Change Slot Settings
    * add Transportation Slot Management: For Rent
    * add Transportation Slot Management: Government
    * add Transportation Slot Management: Private
    * add Transportation Slot Management: Civic

   * (2015-9-05)

    * fix bug w inflict army damage
    * fix bug w showing char names w special chars in chat list
    * add Daily Award: Use Forum Opinion
    * add Daily Award: Be in Chat > 2 minutes
    * add Daily Award: Share on Twitter
    * add Daily Award: Share on Facebook

   0.7.14.1

   * (2015-9-04)

    * add Daily Award: Contribute to Scenario
    * add Daily Award: Market Transaction
    * add Daily Award: Participate in Battle

   * (2015-9-03)

    * add Daily Award: conditional regen amount / bonus
    * add Daily Award: conditional Xp amounts
    * add Daily Award:Participate in Duel
    * add Daily Award: reward message
    * fix bug w duel take action
    * fix bug w duel targeting
    * add Daily Award:Visit Home
    * add Daily Award:Visit Work

   * (2015-9-02)

    * fix bug w do action results
    * add Daily Award: Perform 3 Actions
    * add forum session handling from game
    * add remove daily award bonuses on day cycle
    * add static ap regen bonus

   * (2015-9-01)

    * add Forum Welcome message on character's first selection of forum
    * add create World topic action: World forums options
    * fix bug w create Settlement topic action character posting
    * add create Settlement topic action: Settlement forums options
    * fix bug w create Novice topic action character posting
    * add create Novice topic action: post content
    * add create Novice topic action: Novice forums options
    * remove create topic options from within forum
    * add refresh opinion info in ui when used in forum

   * (2015-8-30)

    * add refresh opinion info in ui when used in forum
    * add opinion info to ui
    * add reputation to opinions in forum messages
    * add contact employees to building view
    * add group messaging
    * add top minister messaging to department ministers

   * (2015-8-29)

    * create forum login action
    * fix bug w private messages
    * add contact landlord to housing view
    * add contact tenants to building view
    * add contact owner to building view
    * fix bug w character forum login attempts

   0.7.14.0

   * (2015-8-28)

    * fix bug w multiple unit position records per combat
    * fix bug w multiple combat records
    * fix bug w attribute name use
    * fix bug w encounter fight combat type
    * add artillery and magic unit images
    * fix bugs w get fatigue on troops w no unit records
    * add deserter unit messages to combat rounds

   * (2015-8-27)

    * add death unit messages to combat rounds
    * add by unit damage messages to combat rounds
    * fix bug w home vs away unit bonus calc
    * fix bug w army array troop type
    * add restore fatigue
    * add Ghoul special ability: restore fatigue on victory
    * add Giant special ability: might x opponents

   * (2015-8-26)

    * add Spirit special ability: take half damage
    * add Golem and Troll special abilities: no death in victory
    * add Lich special ability: raise killed enemies as skeletons / zombies on win
    * fix bug w verbose vs concise attribute data returns

   * (2015-8-24)

    * fix bug w bonus amount by extant unit calc
    * add own army special ability attribute penalty
    * add opposing army special ability attribute penalties

   * (2015-8-23)

    * add unit special ability: opposition tactics effects penalty
    * add unit special ability: overwatch defense
    * add unit special ability: all damage
    * add unit special ability: range resistance
    * add unit special ability: range bonus

   * (2015-8-22)

    * add deserters checks for current combat army attribute calc
    * add get troop attributes by individual troop or by army
    * add consolidated unit special ability attribute bonus checks
    * add troop home settlement

   * (2015-8-21)

    * add consolidated troop attribute request
    * add consolidated troop equipment and attribute bonus calc
    * fix bug w troop type detection on attribute request
    * add Zombie special ability - immune to fatigue
    * add opposing army tactics effect to combat records
    * add new unit special abilities to catalog
    * add unit names to individual unit records

   * (2015-8-20)

    * fix bug w auto generate mediawiki actions pages
    * fix bug w facebook account records
    * add monster option to encounter opponents by rank
    * fix settlement info in fight
    * fix monster in training options (removed)
    * fix bug w Artillery attribute bonuses
    * add Artillery and Magic to unit battle types
    * add Flying and Wheeled to unit mobility types
    * fix json response on clear form message
    * fix json response on market back / next page
    * add monster unit to simulated combat opponent options

   * (2015-8-19)

    * add php7 handling for mediawiki symfony auth
    * add php7 handling for phpbb private messaging
    * add php7 handling for phpbb quoting
    * add php7 handling for phpbb message parsing
    * add php7 handling for phpbb bbcodes

   * (2015-8-17)

    * add monster unit images
    * add artillery, magic unit catalog categories
    * add multiple population requirement unit training
    * add magic, artillery, monster equipment access
    * add monster unit population type
    * add magic, artillery, monster catalog descriptions

   * (2015-8-16)

    * add magic unit crafting
    * add artillery unit crafting
    * add unit types to units

   * (2015-8-15)

    * add supervisord sustained chat server

   * (2015-8-14)

    * fix bug w chat message delivery
    * add send chat message on 'return' keypress
    * fix bug w leave chat room
