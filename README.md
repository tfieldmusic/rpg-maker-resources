# Master List of Scripts

- **[Advanced Game Time](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/advanced_game_time.rb):** Set and recall the current game time; tints screen to give the appearance of time of day.
- **[Advanced Game Time Save Screen](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/advanced_game_time_save_screen.rb):** Shows the current time instead of total play time on save games. Used with Advanced Game Time.
- **[Auto Loader](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/auto_loader.rb):** Automatically loads all scripts in `/Scripts` so you can manage and version them like code instead of binary files.
- **[Basic Window Resizer](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/basic_window_resizer.rb):** Scales the display up to whatever size you want to display your game at.
- **[Better Game Timer](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/better_game_timer.rb):** Extensions to the game timer to add/subtract time, or pause/resume. Also displays time in red when remaining time is some threshold (eg. 30s)
- **[CSCA Achievements](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/CSCA_Achievements.rb):** Adds an extensible achievement system to your game. Requires the [CSCA Core](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/CSCA_Core.rb).
- **[Expose Data](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/expose_data.rb):** Converts .rvdata2 files into plain text so you can easily see/diff changes during development.
- **[Image Title Menu](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/image_title_menu.rb):** A custom title-menu script that allows you to use images for the menu options, and specify your own custom commands.
- **[Jet Mouse System](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/jet_mouse_system.rb):** Adds full mouse support tp RPG Maker: menus, moving on the map, interacting with events, etc.
- **[Jet Splash Screens](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/jet_splash_screens.rb):** Adds custom splash-screens to your game before the titlescreen.
- **[Lemony's Current FPS](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/lemonys_current_fps.rb):** Gives you script access to the current in-game FPS.
- **[Lemony's Sound-Emitting Events](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/lemonys_sound_emitting_events.rb):** Create sounds on events that change in volume based on your proximity to them.
- **[NerdiGaming - Title Menu](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/nerdigaming_title_menu.rb):** A custom title-menu script that allows you to use images for the menu options. (This script is no longer maintained; Image Title Menu succeeds it.)
- **[Points System](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/points_system.rb):** A simple system for giving and tracking points programatically.
- **[Proton Analytics](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/proton_analytics.rb):** Game integration with [Proton Analytics](http://www.protonanalytics.com) to track users, sessions, and events.
- **[Proximity Detection Script](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/proximity_detection.rb):** A script to detect if the player is (or isn't) within a certain distance of events.
- **[QFRJ Misc Scripts](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/qfrj_misc_scripts.rb):** Some miscellaneous scripts related to events and party health
- **[Vector Engine Light Effects](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/vector_engine_light_effects.rb):** Field-of-view style lighting. Requires the [basic module](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/vector_engine_basic_module.rb) and [light images](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/victor_engine_light_effects_images.zip).
- **[Window Timer](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/window_timer.rb):** Allows you to add a timer for choices and message windows so that they automatically close after the specified time.
- **[Word Wrapping](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/word_wrapping_by_killozapit.rb):** Automatically wraps messages to fit to the window width.
- **[Xail System Title Screen](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/xail_system_title.rb):** Customize the title screen to add new menu items, and icons. Requires the [XS Core](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/xail_system_core.rb).
- **[Xail System Credits](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/xail_system_credits.rb):** Provides a mechanism for showing a credits screen. Integrates with Xail System Title Screen; requires the [XS Core](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/xail_system_core.rb).
- **[Yanfly Engine Ace - Ace Item Menu v1.02](https://github.com/ashes999/rpg-maker-resources/blob/gh-pages/vx-ace/scripts/ace_item_menu.rb):** A better item menu that displays items grouped categorically, as well as with large, custom images.


# What is this?

RPG Maker is an awesome game-making tool by EnterBrain. The core game comes with some resources, and you can extend it in a multitude of ways. Unfortunately, there are two big problems with finding scripts right now:

1. **Link Rot:** Sites move or go down. DropBox quotas run dry. You can't always get access to scripts you want.
2. **Versions and Attribution:** most scripts are scattered in the RPG Maker forums (or elsewhere on the net)

There is a need for a single, central repository of scripts (just like Ruby's Gems, Java's Maven, or C#'s NuGet). Users can always get access to scripts, and authors can update their scripts freely, giving us a *single, always up-to-date place to get access to scripts.*

That's what this repository is. Feel free to browse and download whatever you wish. (Future versions may include a local search client.)

**How you can help:**

- **Add scripts:** Send us pull requests to add or update your scripts.
- **Link scripts:** Link our [home page](http://ashes999.github.io/rpg-maker-resources) wherever you're sharing your scripts, so people can find a copy if your copy becomes unavailable.
