   CHANGELOG for 0.8.0
   ===================

   0.8.0.3

   * (2015-11-16)

    * add to research service: get research topic choices
    * add to research service: get research buildings by district
    * add to research service: get research districts
    * add subtype to research technology records
    * add bonus target to research science records

   * (2015-11-15)

    * add set research service method
    * add select research form to building management view
    * add select building research form
    * add select research group form
    * add select research district form
    * add select research building form

   * (2015-11-14)

    * add select research type form
    * add select research subtype form
    * add research form controller
    * add research subtypes

   * (2015-11-12)

    * add new attribute base amounts
    * add messaging for conditional law access

   * (2015-11-11)

    * add law access by economy type
    * add change market access by law
    * fix bug w negative forum opinion total effect
    * fix bug w forum opinion access

   * (2015-11-04)

    * fix bug w action cost calc
    * fix bug w district access
    * fix bug w encounters blocking gameplay
    * fix bug w bundles in repo

   * (2015-10-25)

    * add remove duplicate scripts
    * fix bug w bio opinions
    * fix bug w character select refresh

   * (2015-10-18)

    * fix bug w initiate vote
    * fix bugs w Custom Law
    * add actions panel to overview
    * remove actions menu drop downs
    * add graphic Actions menu

   * (2015-10-17)

    * fix bug w district happiness view
    * fix bug w notifications
    * fix bug w actions overview toggle
    * update combat defender view
    * update combat attacker view
    * add combat round view
    * add view combat report
    * add prepare combat to simulate combat
    * add duel to simulate combat
    * add equipment to simulate combat

   * (2015-10-16)

    * add civic system bonuses to get char army bonuses in attribute service
    * add traits bonuses to get char army bonuses in attribute service
    * add get zodiac defense bonus to attribute service
    * add get zodiac damage bonus to attribute service
    * add get phase damage bonus to attribute service
    * add morale tracking to combat records
    * add deserted units tracking to combat position records

   * (2015-10-14)

    * add apply army bonuses to attribute service
    * add bonus data to get char army bonuses
    * add get non combat army array to attribute service
    * add get phase magic resist effect to attribute service
    * add prevent units acting as transport crews from joining combat armies
    * add army object
    * add default unit fatigue
    * add hit, miss, crit to combat position records
    * add mana point cost to combat position records
    * update combat bonus records w category and id
    * add unit special ability desc records
    * add test for combat: Raid
    * add test for combat: Duel
    * add test for combat: Battle
    * add test for combat: Encounter
    * add examine combat bonus records command

   0.8.0.2

   * (2015-10-12)

    * add: Time of Troubles abandoned Settlement decay

   * (2015-10-10)

    * fix bugs w Diplomacy Council actions

   * (2015-10-7)

    * add Server Broadcast Message
    * fix bug: hero selection element blocking
    * fix bug: government prisoners
    * fix bug: tax report on lack of transactions
    * fix bug: Annul Friendship selection refresh
    * fix bug: alter records percentage target
    * fix bug: Basilica fixture spelling
    * add Colonnade bonus from static to percentage

   * (2015-10-6)

    * fix bug: missing settlement id
    * fix bug: Hero attribute bonus effects
    * fix bug: Hero attribute access
    * fix bug: Hero rank achievements
    * fix bug: access to district blueprints

   * (2015-10-5)

    * fix bug: fix bugs w access to world market from wilderness
    * fix bug: fix bugs w forum group access

   0.8.0.1

   * (2015-10-4)

    * fix bug: Annul Friendship option not appearing on personal relationships when available
    * fix bug: settlement government, economy, society defaults unselected on first Government->Overview load
    * fix bug: Resurrection does not consume mp
    * fix bug: Bless Building does not consume mp
    * fix bug: Fast and Pray results in decimal mp
    * fix bug: Ritual of Plenty does not consume mp
    * fix bug: look for work display
    * fix bug: default Hero bio refers to "Lord"
    * fix bug: eye button on forum posts unresponsive
    * fix bug: Silver Harvest Skill not resulting in Scythe Swinger achievement

   * (2015-10-3)

    * fix bugs w applying opinions to character bio
    * fix bug: characters unable to use opinions in forums
    * fix bug: perpetual homelessness
    * fix bug: heretics, criminals, vampires handling
    * fix bug: population on building mode change incorrect

   * (2015-10-2)

    * fix bug: encounter / adventure overspawn
    * fix bug: characters stuck in bugged encounters

   * (2015-10-1)

    * fix bug: fix bugs w encounter fight completion
    * fix bug: fighting in encounter triggers endless load

   * (2015-9-30)

    * fix bugs w Declare Enmity and Declare Rivalry actions
    * fix avatar editor access bug
    * add players who have made a purchase option to automated emails
    * add players w Hero characters option to automated emails
    * add players w Lord characters option to automated emails
    * fix bug w Unsubscribe option in automated emails

   * (2015-9-29)

    * fix bugs w share options in notifications
    * fix bugs w automated email messaging
    * fix bugs w automated email templating

   * (2015-9-28)

    * fix bug w admin character load
    * fix bug w notification tally
    * fix bug w notification last notice id
    * fix bug w forum sessions
    * fix bug w notification linking
    * fix bug w private message building owner
    * fix bug w district building load
    * fix bug w save settlement flag

   * (2015-9-27)

    * fix bugs w notification image paths
    * add json return / js render for notifications (performance)
    * add single call notification request (performance)

   * (2015-9-23)

    * fix bug w select Knack messaging
    * add action view option: all available
    * add new default action view: only currently doable
    * add new action buttons

   * (2015-9-22)

    * fix default forum width
    * add messaging / helpful links when cannot perform action
    * fix bugs w partial / full page loads
    * fix bug w Government->Foreign Nationals load

   0.8.0.0

   * (2015-9-22)

    * add discontent detail view
    * add discontent meter to Manage->Government->Interior->Population
    * add discontent meter to Manage->Government->Overview
    * add Populace discontent request: change economy
    * add Populace discontent request: change society
    * add Populace discontent request: change government
    * add Populace discontent request: denounce other settlement
    * add Populace discontent request: praise other settlement

   * (2015-9-21)

    * add Populace discontent request: building downgrade
    * add Populace discontent request: building upgrade
    * add Populace discontent request: building construction
    * add Populace discontent request: repeal law
    * add Populace discontent request: promote minister
    * add Populace discontent request: fire minister
    * add Populace discontent request: hire minister
    * add Populace discontent request: change religion
    * add Populace discontent request: change culture
    * add Populace discontent request: change philosophy
    * add Populace discontent request: join coalition
    * add Populace discontent request: leave coalition
    * add Populace discontent request: create diplomatic bond
    * add Populace discontent request: sever diplomatic bond
    * add Populace discontent action: positive happiness scenario
    * add Populace discontent action: sell to market
    * add Populace discontent action: purchase from market
    * add Populace discontent action: give item
    * add Populace discontent action: give good
    * add Populace discontent action: give resource
    * add Populace discontent action: decommission transport
    * add Populace discontent action: negative happiness scenario
    * add Populace discontent action: change immigration policy
    * add Populace discontent action: recruit transport
    * add Populace discontent action: recruit troops
    * add Populace discontent action: downgrade building
    * add Populace discontent action: upgrade building
    * add Populace discontent action: building construction
