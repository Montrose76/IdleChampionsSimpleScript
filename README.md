# IdleChampionsSimpleScript
This is a simple AHK script for the game Idle Champions. 
To use this, download "Simple.AHK" to your machine. You will also need to install AutoHotkey (https://www.autohotkey.com/).  

Once you have done all that, run the Idle Champions game and start the Mad Wizard adventure. Run through that adventure until you
have enough gold to buy the champs you want. Put them into the spaces you want. Put a familiar on click damage and Put a familiar 
in the field. Save that formation into the "Q" spot. You only need to do this one time.

After that, you should be good to go. End the current adventure to return to the map screen of Idle Champions. Double-click the AHK 
file to load it. Press F2 to begin the farming script.

See below for requirements, known issues, and hot keys.

;  ------ READ THIS SECTION ----- READ THIS SECTION ----- READ THIS SECTION ----- READ THIS SECTION ----- READ THIS SECTION ------ 	;
;																																																																		;
;     REQUIREMENTS																																																									;
;       -- Resolution Setting must be 1280x720																																											;		
;       -- You must have a formation saved to the "Q"																																								;
;       -- You must have the champions that you wish to be in your formation, in their appropriatte places in the "Q" formation			;
;       -- You must have at least two familiars saved in your "Q" formation --> One on click damage and one on the field clicking		;
;       -- You must not have a familiar levelling a champion. If you do, their special dialog will pop and the script will fail			;
;				-- You should not place a familiar on ultimates, as champions will not be levelled to the point that they have ultimates		;
;																																																																		;
;  ------ READ THIS SECTION ----- READ THIS SECTION ----- READ THIS SECTION ----- READ THIS SECTION ----- READ THIS SECTION ------ 	;

;-----------------------------------------------------------------------------------------------------------------------------------;
;	Mad Wizard Gem Farming Script																																																  		;
;	This script is designed to farm gems through low level areas, then reset and start over again																			;
;	This script is based on a fantastic script by Bootch, thanks Bootch! 																															;
;	The original script was written by Hikibla, thanks Hikibla!																																				; 
;-----------------------------------------------------------------------------------------------------------------------------------;

;-----------------------------------------------------------------------------------------------------------------------------------;
; Known issues - Known problems with the script																																											;
;	Having the title bar turned off will create a shift in the Y values and script won't be able find several Locations.							;
;	Pausing the script while on a boss level may confuse the level counter. The script may still work but will run an extra level.		;
;	The script may not work if you are running game in full screen mode																																;	
;	Updates from CNE occassionally break the script																																										;
;-----------------------------------------------------------------------------------------------------------------------------------;

;-----------------------------------------------------------------------------------------------------------------------------------;
;	Hotkeys - Controls for the script																																																	;
;	`		: Pause the script																																																						;		
;	F1		: Toggle the tooltip with the hotkey Info																																										; 
;	F2		: Start the script to farm Mad Wizard																																												;
;   F5		: Nothing to see here (Reserved for debugging)																																						;	
;	F9		: Reload the script																																																					;
;	F10		: Exit the script																																																						;
;	Up		: Increase the Target Level by 10																																														;		
;	DOWN	: Decrease the Target Level by 10																																														;
;	Q/W/E	: Temporarily use the Q/W/E formation until the next script reload																													;	
;-----------------------------------------------------------------------------------------------------------------------------------;


