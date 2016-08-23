# Session16BroadcastReceiver

Create the BroadcastReceiver and thereby overriding the onReceive() method. Use the BatteryManager
intent and get the battery percentage and update the UI with the Battery percentage.


Intent.Action_Battery_Changed-
A sticky broadcast containing the charging state, level, and other information about the battery.

BatteryManager.Extra_Level
 Integer field containing the current battery level, from 0 to EXTRA_SCALE.
 
 BatteryManager.Extra_Scale
    Integer containing the maximum battery level.
    
registerReceiver(BroadcastReceiver receiver, IntentFilter filter)
 register for Action_Battery_Changed broadcast 
 
 
