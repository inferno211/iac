# iAC v1.0 (AntyCheat for SA:MP 0.3.7 R2)

          iAC [v1.0 Beta]
      (c) Copyright 2013-2016 by Inferno
 
	  @author    : Inferno (https://github.com/inferno211)
	  @contact 	 : inferno.piotr@gmail.com
	  @date      : 14 marca 2016
	  @update    : 14 marca 2016


	  DOCUMENTATION

	  	function
	  		GetPlayerImmunity(playerid);
	  		SetPlayerImmunity(playerid, status);
	  		TogglePlayerControllableEx(playerid, bool: toggle);
	  		GetTogglePlayerControllableEx(playerid);
	  		TogglePlayerSpectatingEx(playerid, toggle);

		event
			OnCheatWarning(playerid, cheatid, warning_points, warning_limit, params[])
			OnCheatDetect(playerid, cheatid, params[])

		ID of cheat
			0 	- Fly
			1 	- AirBreak
			2 	- jetpack
			3 	- freeze
			4 	- spectate
			5 	- car
			6 	- fakekill
			7 	- rcon hack
			8 	- vehmodcrasher
			9 	- seatcrasher
  			10 	- reconnect (not used!)
  			11 	- ping
