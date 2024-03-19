How It Works:
Input Boolean: Represents the presence of the residents. It's initially set to off (indicating not both are present). You can create this from the Home Assistant UI instead if preferred.
Automation: This listens for changes in the state of the two device trackers. If both are 'home', the input boolean (input_boolean.residents) is turned on. If either or both are not home, the input boolean is turned off.
Adjustments Needed:
Replace device_tracker.person1 and device_tracker.person2 with the actual entity IDs of the device trackers you're using.
The input_boolean will need to be created through the Home Assistant UI for full functionality or to match your exact requirements.
