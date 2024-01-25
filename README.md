# DayZ-JAS-Prison-Riot-PvP

Place the spawnGearPresetFiles json into the "custom" folder.

Backup the original cfgPlayerSpawnPoints.xml, and upload the supplied one.

Add this line to your cfggameplay.json in the "PlayerData" section, see example below:


"PlayerData":
	{
 		"disablePersonalLight": [true/false],
 		"spawnGearPresetFiles": ["custom/PrisonerPvPLoadout.json", "custom/PolicePvPLoadout.json", "custom/PoliceORELPvPLoadout.json"],   <-- Add this line
 		"StaminaData":


After all files have been edited and uploaded, restart the server for the changes to take effect.
