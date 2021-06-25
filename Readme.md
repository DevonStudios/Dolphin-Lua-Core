# Dolphin Lua Core + TAStudio (custom Dolphin build with some Pokémon games fixes)

This project adds Lua support and TAStudio interface in the revision 5.0 of Dolphin Emulator. The Lua API is based on Dragonbane0's Zelda Edition, which can be found [here](https://github.com/dragonbane0/dolphin).

There are also some fixes to make initial seed RTC abuse possible in Pokémon Colosseum / Pokémon XD and to make linking to VBA/mGBA correctly work in Pokémon Box (all regions).

## Lua Core

### Running scripts

To run already implemented Lua scripts, go to `Tools` - `Execute Script`. In the new window, select the desired script (note that only Lua scripts in `\Sys\Scripts` folder are shown in the list) and click on `Start` whenever you want to execute it. To stop the script execution, click on `Cancel`.

**Important**: Please note that closing the `Execute Script` window does NOT stop the script execution. You have to click on `Cancel` while the desired script is selected to do so.
