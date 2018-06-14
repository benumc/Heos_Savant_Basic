# Heos_Savant_Basic
Simple IP integration of Heos units for volume control and source selection.


  The setup takes a few steps at the moment as I couldn't think of a way to enumerate the sources on the fly.
  
  Profile should work with all heos models.
  
  Does not provide LMQ in anyway.
  
  Make sure the Heos device is setup with a static/reserved ip.
  
  Add profile to blueprint, connect ethernet and enter IP address on the wire.
  
  Upload
  
  Browse to system monitor -> System State and find the Source Names by searching for "AuxInput".
  
  You should see a list of each discovered Heos Input with a number.
  
  Using that number, you can make your audio connections in blueprint.
  
  To get your Hostname, while in System Monitor -> System State, search for “PID_”. 
  
  You should see a list of all of the Heos players and their IDs. IDs are listed under the State Value column.
  
  Enter the ID in the hostname field exactly as shown.

  Finally upload and test.
