Social Distancing Tracker
----------------------------------------------------
This app helps you keep track of your social distance when outside.

### How it works
The app uses bluetooth to get nearby devices. It uses location information to detect if you have visited new places.

### UI/UX
The UI is very minimalistic and easy to use. The screens are clutter free, with refreshing color schemes.

### Testing
For testing, you can reduce the crowd threshold by reducing the value of 
the crowdThreshold variable in the MapsActivityCurrentPlace.java. You can also remove the filters
to include all bluetooth devices in the onReceive() function in the BluetoothService file.  
