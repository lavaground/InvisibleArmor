#Invisible Armor v1.01



Mod incuded:

- Invisible Armor

------------------------------------------------------------------------------------------------------------------------

Changelog:

v1.01

- Updated Hook

v1.00

- Release

------------------------------------------------------------------------------------------------------------------------

Installation / Updates (if NO other mods are used):

Extract the contentes of the zip file to your [pd2_root] folder

========================================================================================================================

Installation / Updates (if other mods ARE used):

- Extract the folder "lib" to your [pd2_root]

- Open your "PD2Hook.yml" and add following to your "PostRequireScripts:" section:

		 - ['lib/tweak_data/blackmarkettweakdata', lib\Lua\InvisibleArmor.lua]

------------------------------------------------------------------------------------------------------------------------

Uninstall:

- Go to your [pd2_root] and delete following folder and files:
         
         "/lib"
         "IPHLPAPI.dll"
         "PD2Hook.yml"

========================================================================================================================

Individual Uninstall:

- Go to: [pd2_root]/lib/Lua and delete the file "Lua"
   	 [pd2_root]/ and delete the entry in "PD2Hook.yml"

------------------------------------------------------------------------------------------------------------------------

Options:

- Open [pd2_root]/lib/Lua/InvisibleArmor.lua and change the number of each "var_model_0X", e.g. "var_model_07" for ICTV
  
  Options are simple: Numbers 1 - 7 are representing each armor type from lowest to highest, for both selected (level) and displayed armor (model). 

  "bm_armor_level_X" is the actual selectable armor type ingame (level)
  
  "var_model_0X" is the armor type that will be displayed. (model)

------------------------------------------------------------------------------------------------------------------------

Notes:

Have fun doing crazy combinations, i like to set it to "LEVEL: MODEL = 1: 1 - 2: 2 - 3: 2 - 4: 2 - 5: 2 - 6: 2 - 7: 2" so i can see a difference if someone is wearing some kind of armor and still enjoy my suit mods ;)

========================================================================================================================

Credits:

Thanks to Olipro for giving me a decompiled version of the needed file xD

------------------------------------------------------------------------------------------------------------------------

Enjoy the Mod :)

Greetz Lava
