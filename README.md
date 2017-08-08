Christmas
=========

[MV]_Christmas, the perfect Filterscript for christmas and newyear for your SA:MP server

# Settings
```PAWN
#define MAX_PLAYERS				60						//Define how much slots your server uses
#define SF						false					//When true it will add some default objects in San Fierro (using 568 objects ! (You can edit it ofc))
#define MAX_BATTERIES			5						//Maximum firework batteries
#define MAX_XMASTREES			30						//recommended - If you have more you might need an object streamer
#define MAX_SNOW_OBJECTS		2						//recommended - If you have more you might need an object streamer
#define SNOW_UPDATE_INTERVAL	750						//time in milliseconds, the interval between the snow
#define NEXT_YEAR				"2017"					//Which year is it next year ?
#define FILE_SAVE				"[MV]_Christmas.txt"	//The name of the file where to save positions too with /savepos
```


# Functions:

```
native CreateChristmasTree(type,Float:x, Float:y, Float:z);
native GiveChristmasHat(playerid,type);
native CreateChristmasLights(Float:x, Float:y, Float:z);
```

Types:
```
TREE_TYPE_BIG
TREE_TYPE_SMALL
TREE_TYPE_SMALL2

HAT_TYPE_1
HAT_TYPE_2
```

Examples
```
CreateChristmasTree(TREE_TYPE_SMALL,-1549.0511,585.0486,7.1797);
CreateChristmasTree(TREE_TYPE_BIG,-1548.4778,646.2723,7.1875);

GiveChristmasHat(playerid,HAT_TYPE_1);
```

# Commands
```
/christmas
/savepos - Dynamicly save christmas trees or lights using your current position
```

# To-do
* Needs a rescript, really.
