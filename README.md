# StoreParachute
Parachutes for Zephyrus Store


add this to your `.\addons\sourcemod\translations\store.phrases.txt`
```
	"parachute"
	{
		"en" "Parachute"
	}
```

add something like this to your `.\addons\sourcemod\configs\store\items.txt`
```
	"Parachute"
	{
		"Rainbow"
		{
			"model" "models/parachute/parachute_rainbow.mdl"
			"price" "1"
			"fallspeed" "80.0"
			"type" "parachute"
		}
		"Blue"
		{
			"model" "models/parachute/parachute_blue.mdl"
			"price" "1"
			"fallspeed" "100.0"
			"type" "parachute"
		}
		"Gargoyle"
		{
			"model" "models/parachute/gargoyle.mdl"
			"price" "1"
			"fallspeed" "50.0"
			"type" "parachute"
			"flag" "a"
		}
	}
```
no need for manual adding to downloader/precacher plugins

find more parachutes here: https://gamebanana.com/skins/cats/11622

used code by zipcore
https://gitlab.com/Zipcore/HungerGames/blob/master/addons/sourcemod/scripting/hungergames/tools/parachute.sp
