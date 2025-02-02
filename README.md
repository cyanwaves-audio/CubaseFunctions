Installation:
For Windows, move them to your <User>\Documents\Steinberg\Cubase\User Presets\Project Logical Editor\ folder

I recommend assigning a key/macro in the Cubase Key Commands for each.


Description and Usage:

CreateCycleMarkersForSelection:
  - Creates cycle markers on selected events (audio, MIDI, video, group).
  - I have it assigned to Ctrl+Shift+P (look for the function name in the Key Commands editor)
  - Requires you to select at least one event and will create marker cycles to the right as long as there are events in the same track.
  - Useful to group your events if you use different sound effects for a single variation (it will add a marker cycle to the whole duration of the group instead of the single event).
  - Use it repeatedly for each event. It will move automatically to the next one, so you can spam it.

GenerateMarkerNumbers_20max:
  - Edits the name of the selected cycle markers, adding an underscore and an ascending number (up to 20, you can add more if you need).
  - I have it assigned to Ctrl+Alt+P
  - Requires you to select all markers you want to edit.
  - I recommend not naming your markers with numbers, as the function works by finding and replacing them.
  - Use it once per selection.

Usage:
  1. Select an event, Ctrl+Shift+P until you have created all the markers you want.
  2. Select all the cycle markers you want to edit.
  3. Rename them according to your basic naming scheme in the status bar (without numbers): like, FootstepsDirt
  4. The cycle markers will still be selected, use Ctrl+Alt+P.
     If, for example, you have 6 markers named FootstepsDirt selected, they will be renamed to FootstepsDirt_01, FootstepsDirt_02... FootstepsDirt_06.
