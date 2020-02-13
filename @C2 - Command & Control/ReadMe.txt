
Command And Control (C2)
Version: 2.01
Author: Mad_Cheese
Type: MOD / Addon
Requires: Arma 3, CBA_A3
Compatibility: SP/MP
Signed: Yes

Description: 

C2 is a powerful tool that aims to maximize your performance when leading AI-squads. 


                                              C H A N G E L O G :


                                                --- V1.0: ---
                                               Initial Release



                                                --- V 1.1: ---

- Name changed to C2 - CONTROL AND COMMAND
- Added: New indicator objects (semi transparent / glow in the dark)
- Added: MOUT style sector coverage for line- and L-formations (3D Mode)
         -> Line formation is now divided in looking left/right
- Added: Building occupation now possible (3d Mode)
- Added: 3d hud formation position can now be locked (User Action 16) -> spacing, formation and rotation changes still work
- Added: Unlimited sync items (planning mode)
- Added and Fixed: Dialog bug when player is in AI driven vehicle -> hold ALT key when clicking on map
- Added: 2 different rotation speeds for 3D Hud-Mode
- Tweaked: Player can now use AI as chauffeurs
- Fixed: Markers changed from global to local
- Fixed: Commands are now only available to group leader
- Fixed: Dummy unit changed to vehicle, hidden globally and not colliding with player anymore
- Fixed: Units 6-10 were broken inn Hud Mode after the 1.4 patch
- Fixed: Now considering difficulty settings (Markers/Lines only visible in interface for VETERAN and ELITE)
- Fixed: Various non gamebreaking scripterrors fixed
 

                                                --- V 1.2: ---

- Added: Smart Building Position-Selection in 3D Mode (detects targeted building-floor) 
- Added: GetTactical Grenades implemented for Player (3D- and Hud-Mode)
         -> Supported Addons: RHS-Escalation, ACE3, SuperFlash
- Added: Supression feature added to both 3d- and Planning-Modes
- Added: Quick-Formation-Selection (Numpad,optional) - get you to your desired formation result much faster.
- Added: New 3D Menu [Functions: GTI Grenades, Rules of engagement, AI-AutoStance, AI-AutoWatch, refresh group, AI-fix-formation]
- Added: AI-Helicopter Control page on tablet
  (options: 4 flying heights, 4 wp types: move/pickup/combat drop/full landing). Interface page tweaked accordingly.
  -> pages can be switched by pressing 1 and 2 in dialog
- Added: New cancel-button for Tablet with 3 modes: cancel current orders (default), cancel planned (shift), cancel current WP only (ctrl)
- Added: Useraction Keybinds replaced by CBA keybinds
- Added: Disband to reserve / rejoin from reserve (Planning Mode -- disbands to HC if enabled)
- Added: New custom markers types
- Added: Tooltips added to all dialogs 
- Fixed: Plans could not be executed after "Stop" command was issued

                                                --- V 1.3: ---
- Added: "Find Cover" feature available in radial menu
- Added: New 'Quick-Spread' formation option to send multiple units to different places with individual sectors much faster in planning mode
- Added: Auto Stance included in HUD mode
- Added: C2_ZEUS-Remote (Shift + LMB on a unit to remote control the group leader, including C2 functions)
- Added: Teamcolor Quick Selectors for HUD mode (F16-F19)
- Added: New Quick-Formation menu (default: Hold SHift + F) as an alternative to the default ~-7-x
- Added: Team Color unit selection available in radial menu
- Added: Simple Bluforce Tracker functionality added to tablet. Player-faction has moving markers, size is reflected, enemy groups can be targeted (rmb on marker)
- Added: Option to toggle controls in planning mode for more map visibility ("FN" hard-button on tablet frame)
- Added: Option to toggle force tracking in planning mode for more map visibility ("A0" hard-button on tablet frame)
- Tweaked: Radial Menu has overhauled usability (hold down key, hover over areas, click on choice)
- Tweaked: Planning mode tablet does no longer close when orders are executed, this MASSIVELY facilitates complex usage and timing
- Tweaked: Looking Direction Marker and Lines are added at mouse-release rather than mouse-press
- Tweaked: Better orientation with Infantry Markers in tablet 
- Tweaked: Num-Block toggle placed in middle of radial menu
- Tweaked: Radial Menu now starts with cursor at center screen
- Tweaked: Script Structure organized better and should be easier to navigate
- Fixed: View direction bug in planning mode (units were always looking at [0,0,0])
- Fixed: Disband to reserve / rejoin from reserve reserves function is fixed
- Fixed: Supression Function now works fine for most part
- Fixed: Tooltips in planning mode are now changing according to page
- Fixed: Useless frame removed from tablet interface
- Changed: Lock Indicator default keybind changed from T to L
- Changed: Supression Hotkey default changed from Y to T (in accordance with default A3 key-mapping)

                                                --- V 1.3.1: ---
- Switched dialogs to displays, player can now walk while using menues
  Note: Formation key has to be initialized by using it once
- Added: HUD mode units can be selected via RMB on teamcolors in radial menu for much quicker access
- Added: All units can be selected/deselected in radial menu (purple)
- Fixed: After executing orders, undo button gets removed now to prevent errors
- Tweaked: GTI Grenade system from radial menu: click on grenade, drag pointer to target, let go of TAB key
- Changed: Radial Menu Keybind from U to TAB
- Changed: Tablet Keybind from DEL to SHIFT + TAB

                                                --- V 1.3.2: ---
- Controls: Controls to adjust the HUD-mode formation are now liberated of the CTRL key
- Fixed: Action menu is now disabled while using menus
- Fixed: Scroll wheel in HUD mode could go in wrong direction
- Fixed: All tablet controls toggle on and off correctly
- Fixed: Mapline bug when unit completes orders while new plans are made 
- Changed: Keybind for Formation menu change from Shift+F to Ctrl+F to avoid sprinting issues
* Changes in HUD mode controls:
* Change Spacing: C2_Ctrl + MouseWheel
* Change Formation: C2_Shift + Mousewheel (or 
* Change Stance: C2_ALT + MouseWheel
* Scroll speed is now depending on actual mouse scroll speed 

                                                --- V 1.4: ---
- Milestone: Hud mode indicators now snap to any surface. Buildings can use positions inside and outside (aim low for outside positions).
- Added: Planning tablet now handles unlimited units via pages
- Added: Units can be dragged on TeamColor buttons in planning tablet. Hold CTRL to drag multiple units.
- Added: Running orders for HUD mode. Forward Peel: CTRL+SHIFT+RMB. Backward Peel:  CTRL+ALT+RMB . Can be overridden.
- Tweaked: HUD mode indicators were improved and now demonstrate unit orientation
- Tweaked: Supression indicator snaps to any position of surface intersect, rendering mousewheel height obsolete
- Tweaked: TeamColor buttons system was overhauled and now work in the same fashion as it does in the radial menu.
- Tweaked: Tablet Tracker groups now receive correct group icons. Size is still reflected visually.
- Tweaked: TeamColor buttons in planning tablet made bigger for better access
- Fixed: 3D-Indicators are now removed if player gets killed 
- Fixed: Action menu disabled while positioning supression indicator
- Fixed: F-Keys unit selection in Planning Tablet work again
- Fixed: CTRL+SHIFT+F# to select units 11-20 in HUD mode works again
- Fixed: Player no longer falsely takes command over a group he was joined into.
- Manual updated

                                                --- V 1.4.1: ---
- ADDED: BuildingPos support for Planning Mode, including visualization of building positions (see updated manual)
- ADDED: Doorkickers style Go-Codes to Planning Mode (right click on waypoint, send order by tablet buttons)
- ADDED: New 3d unit-selection.  CTRL+RMB on unit to select in A3, CTRL+ALT+RMB on unit for HUD selection
- ADDED: Simple AI rearm function added to radial menu
- FIXED: Drivers no longer get out of vehicle when player is commander in planning mode
- FIXED: Pilot now stays reactive when dismounting after final landing
- FIXED: When not on foot, HUD-indicators don't snap to player's vehicle anymore
- FIXED: Issue with force tracker markers hopefully fixed
- TWEAKED: HUD-mode selection changed to CBA keybinds for more customability
- TWEAKED: Mapline system completely reworked to be flexible
- TWEAKED: Tablet markers changed to dots for less clutter
- TWEAKED: Tablet interface can now also be closed via it's keybind
- TWEAKED: Maxed out AI skill can now be toggled off in init.sqf (MCSS_C2_ADJUSTSKILL = false;)
- TWEAKED: Manual updated with pictures, hopefully for better understanding.


                                                --- V 1.4.2: ---
- ADDED: Planning Mode Waypoints/Looking Dir Markers of single units can now be dragged with LMB in real time! (exeption: Buildings, GoCodes)
- ADDED: Remote M203 function. Works just as supression but with GTI-grenade key
  -> unit must have Gr-Launcher and sight on target. Selecting multiple units will filter a unit that has a shot.
- ADDED: If DEV-build (or >V1.54) is detected, unit's AUTOCOMBAT can be disabled in radial menu
- ADDED: Full stance control in radial menu
- ADDED: Building Click in Planning Mode now also shows door locations of a clicked building (direction not accurate)
- ADDED: Planning Mode mapcursor now shows relative direction
- FIXED: Waypoint conditions for buildings are now reliable enough for sequences!
- FIXED: Bug when unit finishes waypoint-session while player is extending it (Planning Mode)
  -> lines now also behave accordingly
- FIXED: Rejoin from reserve works correctly again
- FIXED: Group Switch bug in campaign (player joins new group but is not leader)
- TWEAKED: Auto_Rearm function overhauled. units can now pick up a new primary weapon. Range extended to 120m
- TWEAKED: Color team Selection changed to RMB context menu until drag/drop bug is fixed
- TWEAKED: Suppression indicator is more visible again
- Manual updated

                                                --- V 1.4.3: ---
- TWEAKED: Heli's now only auto-dismount units that are non pilot/helicrew-class and not occupying weapon turret
- TWEAKED: Planning Tablet: RelDir display now contains distance and is only displayed while mouse hovers over map
- TWEAKED: Heli pickup/dropoff script improved
- FIXED: 3DEN-Update AutoDanger Bug fixed (DEV build no longer required)
- FIXED: 3DEN Editor initialization bug fixed


                                                --- V 1.4.4: ---
- ADDED: HighCommand control page added to planning mode tablet. Waypoints can be moved and added on the fly.
         -> units can be disbanded to HighCommand and rejoined to group. Includes non disbanded HC-groups
- ADDED: Custom HighCommand function added if player is not synced to HC-module. Functionality is very similar to default HighCommand (beta)
- ADDED: Waypoint loops added to planning mode (beta). Replaces the old Sync-Function. Sync is now exclusively done through Go-Codes.
- ADDED: New right click context menu in planning mode with more settings to adjust, interacts in real time.
- ADDED: Planning Mode waypoints can now be deleted individually
- ADDED: "FIRE ON MY LEAD" option added to ROE-Section of radial menu (selected units hold fire until player fires weapon)
- ADDED: "UNSTUCK AI" added to Radial Menu: Resets unit, teleports unit/vehicle to empty position if no line of sight to enemy within 200m. (TAB + SHIFT + MB)
- ADDED: Brain-Button on radial menu now resets stance and looking direction to "AUTO" (mini-macro)
- TWEAKED: Disable AutoDanger now cancels target before disabling AutoDanger, this has an impact on behavior.
- TWEAKED: Radial menu selects all units by default if selection was empty upon opening. Function Tweaked for convenient usage with TeamColors.
- TWEAKED: "AUTOCOMBAT" is automatically disabled for Helicopter Waypoints (Planning Mode)
- TWEAKED: Pilot's are excluded from re-enabling "AUTOCOMBAT" since it has no benefit to them
- TWEAKED: Planning Mode Waypoint-Markers slightly bigger now for better interaction
- TWEAKED: Disbanded HC groups can be joined back individually
- TWEAKED: Target orders assigned via tablet will now be distributed over crew (if they have a turret)
- FIXED: Re-joining units from reserve will no longer lose data of current planning session. 
- FIXED: Vehicle drivers would dismount on disband/rejoin/refresh
- FIXED: Player's group would lose all knowledge of disband/rejoin/refresh
- Manual updated

                                                --- V 1.4.5: ---
- FIXED: markers ended up in global and would not get removed on machines they were not local on.

                                                --- V 1.4.6: ---
- FIXED: Addon would switch unit sides in 3DEN Editor
- FIXED: "LineMarker" entry added to tablet configs (No more gnarly PopUps)
- FIXED: "FIRE ON MY LEAD" - Function no longer screws up unit's teamColor and orders
- FIXED: Indicators and HUD-Elements now get deleted if unit dies while in active selection
- ADDED: Formation Menu is now also included in radial menu. Hovering over area will add a frame for better vision
- ADDED: GLOBAL PREFERENCES added to radial menu (replaces NUMpad icon). Contains: Skill Reset, Suppression Mode, NUM-Controls
- ADDED: Player can now choose from A3-Supression or C2-Suppression model via preferences (WIP!!!)
- TWEAKED: Unitpos-Icons in radial menu change colors depending on visionmode
- TWEAKED: C2-Groupdata changed to fsm and tweaked to handle bigger changes
- TWEAKED: Suppression selection now works like radial menu (if no units are pre-selected, addon will select all units by default)


                                                --- V 1.4.7: ---
- ADDED:   New Radial-Menu design. Changes color at night for visibility.
- ADDED:   MEDICAL FUNCTIONS added to Radial Menu. Can handle multiple healers and patients at once.
- ADDED:   VEHICLE FUNCTIONS added to Radial Menu. Handles multiple ways of boarding units. 
- ADDED:   ITEM-SECTION added to Radial Menu: Attach/Detach Suppressors | Toggle Pointers | Switch Gun/Pistol | Attach IR_items
- ADDED:   GoCode Activation added to radial menu (RMB on STANCES)
- ADDED:   GTI-GRENADES now support any grenade-type in PLANNING MODE and RADIAL MENU
- ADDED:   GRENADE POOL >> When multiple units are selected, all their throwable items are gathered. 
           >> C2 then uses suitable units to throw the item. (HUD MODE selects one unit, planning mode selects all units that carry the item)
- ADDED:   "KEEP STANCE" option added to HUDMode-stances as NEW DEFAULT ( >> black icon: Current Stance >> white icon: "AUTO" >> yellow icons: "UP"|"CROUCH"|"PRONE")
- ADDED:   CURSORTARGET unit selection added to Radial Menu (point at teamMember and open Radial Menu to select only that unit)
- FIXED:   Regular RClick clears HUDMode Selection again
- FIXED:   Minor fixes on ReArm script. Function still needs overhaul, player still needs to repeat with multiple units.
- TWEAKED: HELICOPTER HEIGHTS changed to: 1000m | 200m | 25m (default) | 5m (not recommended)


                                                --- V 2.0: ---

* ADDED: MAP-PLANNING.
	* Planning Mode capabilities added to main map-display (Toggle overlay with "C"-Key)
	* New overlay is a more compact and powerful version of Planning Mode
	* Planning Mode now has the same Unit Selectors as the radial menu (displaying teamColor and name)
		* buttons also have same SHIFT- and CTRL functionality for faster selections
* ADDED: SUPPRESSION ZONE SYSTEM
	* Suppression is now treated and displayed as a polygon which can handle large areas
	* Suppression Zone is displayed on map, similar to VBS Tactics.
	* Polygons/Zones assigned by planning mode can be resized
		* Hold CTRL, click on main zone-marker, then drag mouse.(WIP but working).
* ADDED: DRAW SUPPRESSION ZONE:
	* New temporary HUD-display with VBS-style Suppression Zone Selection (default: SHIFT + T)
	* Drag LMB over Screen to create zone
	* Old Suppression (target object) can still be used and creates a 5-10m suppression area. Use this to suppress 'snapped positions' such as windows for example.
* ADDED: C2-HC: WAYPOINT ACTIONS.
	* Available so far: Suppression, Ambush, Landing, Combat-Landing (heli only). Coming Soon: Defend, Plant, Throw
	* Right click on HC-waypoint and select options for the waypoint and the waypoint action
	* waypoint action is a script plus an inserted waypoint that waits for the action/condition to be fulfilled
	* Conditions to complete Actions: Timeout, GoCodes, DayTime (within 30min for ambushes etc)
* ADDED: New Right Click Context menu for HC waypoints to configure conditions/formations for waypoints and their actions
* ADDED: Smart-Pages added to planning mode
	* no more need to switch between Ground and AIR pages, C2 does it for you as you select units
		* Non suitable- / cargo units are still greyed out
	* Teamcolor Buttons will choose page according to roles of units (more AIR units than ground will select AIR-page)
		* Purple/All will select all units according to role/page 
		* When current page is HC-page, page will switch according to class
	* HC-groups can be quick selected with rightClick on groupIcon
		* with BIS-HC, select with leftClick
* ADDED: C2-PlugIn for AIC/Advanced AI COMMAND (by DUDA123)
	* waypoints can issued through main map-planning overlay's HC page
	* HC-quick-select compatible (right click on AIC group icon)
	* HC-WP-Menu compatible (right click on AIC wp-icon)
	* HC-WP-Actions-compatible
	* C2-Overlay is hidden while AIC-commandingMenu is open to preserve MMB functionality
* ADDED: Classic WP-SYNC reintroduced. Works just like loops, CTRL + MouseDrag
	* LOOP is selected over SYNC if waypoints belong to the same unit 

* ADDED: Assign/Unassign NVGoggles added to radial menu
	* (Items >> IR_LASER >> Assign NVG: Shift + lClick || Unassign NVG: Shift + rClick)
* ADDED: Keybind-Alternative to send units to HUD-indicator positions (binds customizable)
	* Regular: Spacebar
	* FWD Peel: Ctrl + Spacebar
	* BWD Peel: Alt + Spacebar
* ADDED: New, unified markers
* TWEAKED: WP-Markers now snap to closest building position when dragged over enterable building
* TWEAKED: markers for WP-HUBS can now be dragged individually
* TWEAKED: Hud-Indicators now snap to buildingpos according to:
	* distance to aimpos
	* closest floor-level to aimpos
* TWEAKED: Position snapping for wp-Hubs (Planning Mode)
	* aims to assist quick orders and tackle the problem with oversized building-mapMarkers
	* units will be spread across line, but will look for objects to snap to/ take cover at
		* leading unit's waypoint will currently not be affected
		* snapping-objects must have armor-value higher tham 100
	* disabled for "SPLIT" and "CIRCLE" formations
	* function is WIP and may be turned into it's own formation
* TWEAKED: Buildingpos Viewer overhauled. Doors now get displayed with correct direction
* TWEAKED: Timeout Value no longer gets reset when closing map/overlay
* TWEAKED: Spacing Values for ground and air wp's no longer get reset when closing map/overlay
* TWEAKED: Planning Tablet discontinued for now. Keeping it around for future usage with drones. Also as backup in case a mission removes the map's DRAW-handlers. Some new functionality may be missing in tablet.
* TWEAKED: FIND COVER function drastically improved. Units also only change position if they have to if they have to.
	* selected units distribute suitable array of cover positions
	* hard cover is preferred, but if only concealment is found it will be selected
	* script checks for soft and hard cover in increments of 15m
* TWEAKED: HUD-indicator snapping improved
* TWEAKED: Planning mode: wp combatmode
	* Red icon: default/engage
	* Blue icon: disengage/at all cost 
		* unit will follow the waypoint regardless of personal safety
* TWEAKED: MapDrawing Setup was entirely re-written in a better format, fixing countless potential errors and opening up massive possibilities for the future
* TWEAKED: UnitMarkers are now displayed in the unit's assigned TeamColor for better overview and to encourage usage of teamcolors
* TWEAKED: C2 suppression system removed, instead the new BIS-suppression is put into a powerful framework.
	* Using custom invisible targets instead of BIS-targets allows for targeting elevated positions (windows, balconies etc)
* TWEAKED: Suppression Targeting improved
* TWEAKED: Highest Heli Altitude is now 500m because the AI can not handle anything above in most cases
* TWEAKED: Additional voice-commands removed since they most likely do not match the right voice or even language.
* TWEAKED: REFRESH Function now also restores keybinds that were deleted by mission-designer.
* TWEAKED: HC-groups still keep their name, but their button gets a tag (RS: Reserve / disbanded groups. HC: HighCommand)
* TWEAKED: All planning pages can be accesed by key (1-3)
* TWEAKED: 'RESET HUD' option added to general preferences (resets HUD-Form to Line and HUD-DIR to PLAYER-DIR)
* TWEAKED: MouseWheel inverted for scrolling HUD-FORM
* TWEAKED: Advanced Rappelling Waypoints improved
* FIXED: Enhanced Movement Support is overhauled but can look glitchy. This is all on my end, not EHM.
* FIXED: Dragging Suppression Indicator was bugged when aiming-position was higher than getPosASL player
* FIXED: Setting individual combatmodes (Fire on my lead) was also changing the unit's Formation-Index.
* FIXED: "regular" HighCommand Groups could not be joined to the player/commander's squad.
* FIXED: Vehicle boarding through radial menu was blocked by dead crew-units
* FIXED: Player can no longer order units to board enemy vehicles (which would not work and end up with killed units)
* FIXED: MouseWheel EVH's now only fire while HUD-Mode is used
* FIXED: Switching PlanningMode-Pages no longer clashes with entering numbers with "1" or "2" in the Spacing- and Timeout-Box
* FIXED: Error when unit reached last waypoint while player was extending the session
* FIXED: SPLIT-FORMATION in planning mode would clash with TeamColor Selection

                                                --- V 2.1: ---
ADDED: STANDBY / CONTINUE commands
	* Units in standby will take cover and standby until ordered to continue. Existing Map plans will remain intact
ADDED: REMOTE AT LAUNCH. Works the same as GL-launch function.
	* units carrying GL and AT will prefer AT over GL
	* AT can shoot into windows now
	* Target indicator picks up and tracks moving vehicles, but only guided missiles will stick to the vehicle while airborne.
ADDED: TIMEOUT-setting in map planning changed to WP-CONDITION. Includes Timeout and GoCodes.
ADDED: Additional keybinds. Not set by default. Meant for Voice Attack, but useful anyways. Have a look at the keybinds menu.
FIXED: Map overlay bleeding into main display 
FIXED: Issue with looking direction with map planned waypoints leading to shaking units
FIXED: Infantry Routes with diminished pace were wrongly canceled
FIXED: Directional Markers of waypoint hubs now stay attached to the main WP-marker when being moved
FIXED: Error with missing direction fixed for FIND COVER function
FIXED: Deleting a final or single waypoint with the rmb context menu would not stop the unit
FIXED: Some functions such as suppression are no longer accessible to subordinate players
FIXED: Opening GPS would toggle the map overlay

                                                --- V 2.1 HOTFIX: ---
FIXED: Script Errors with ROE functions
FIXED: disableAI scriptErrors after TacOps patch

                                                --- V 2.1.1 ---

FIXED: Map UI could bleed out of screen depending on interface size setting
FIXED: Mod no longer clashes with the THE FORGOTTEN FEW misison
ADDED: Force Tracker can be disabled in init.sqf (MCSS_C2_DISABLE_TRACKER = true;) >> Exile missions etc

                                                --- V 2.1.2 ---

FIXED: Grenade and Suppression WP-Actions could not be selected
FIXED: WP-Conditions could not be selected

                                                   C R E D I T S :

- GTI ("Get Tactical Interface") Grenade throwing taken from "GTI-GetTacticalInterface" addon, developed by ZAPAT
  -> http://forums.bistudio.com/showthread.php?182473-GetTactical-a-tactical-RTS-interface
- Smart BuildingPos Selection co-developed by Zapat 


                                                   D I S C L A I M E R S :

- AI-Pathfinding is NOT altered. Vehicle Routes work perfectly but can suffer from the famous obstacle hugging AI.
- A3's path-lods are, at the current time, limited. This is mainly an issue in buildings, where units do not behave 100% realistically. 
  However, it can also be a problem outdoors in some cases . 



                                               K N O W N  I S S U E S :
- Action menu not working? Just bring up the radial menu or planning tool once and it will work again
- Anything not working or displayed correctly? Something messed up C2's data - Use the refresh function.
- C2 Vehicle Boarding can currently not make units board a moving vehicle (ie landing chopper)
- Some missions can interfere with the reserve/Highcommand function (ie classify units as obsolete and delete them)
- Dynamic Combat Ops Mission clashes with AI_RAIL, somehow the player gets railed as well. deactivate the function in radial menu for this mission.
- Hovering over tablet placed HC-waypoints throws a scripterror relating to wp-statements. this has no effect, statements are executed perfectly.
- Some visualizations regarding loops can be buggy 
- WLA (whole lotta altis): refresh your group every time you spawn/respawn/fastTravel/join units to group etc as the mission uses a mysterious way
                           Also, HUD mode's 3d-icons and numbers will only work when WLA'S UI is disabled (Shift-U).





