#  timer #

Timer adds functionality to measure time with a timer. The app requires that the ActiveInspector has a field named "time" and that the VBA-sub "SaveTime" is added to the ActionPadTools Module. 

Timer will always load the time spent (in minutes) from the time field. When saving your time, timer will round up to the closest minute.

Insert the following html tag in the actionpad where you want it to be shown, for example in the helpdesk actionpad.

	`<div data-app="{app:'timer'}"></div>`

CREATED BY: JKA