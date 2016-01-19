# Stateless-Scene-via-Echo
SmartApp used in conjunction with a custom momentary button tile that allows for on/off commands to always work regardless of previous state.

One common issue when using Echo to control ST things is that virtual switches created specifically for Echo can become out of sync with their respective physical devices due to delayed status updating (Harmony for instance), use of a non-ST control method or sync that only goes one way. This app intends to provide a new stateless momentary button that can trigger different actions for on or off. 

In this initial beta release there is a parent/child SmartApp and a custom momentary button tile to install. The momentary buttons are not currently child devices, so they will need to be created manually via the IDE for use in the app.
