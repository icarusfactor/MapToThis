# MapToThis
Google Map/GPS/Key/PDF Game

 Want to make a game app with a simple PDF viewer and Google Maps w/GPS using
a unique key and PHP server hosting the GPS positioned detination and PDF files. 
 The object of the game would be for the exhibitor to create a key and destination on
 the server for the scouts to search for with app and device in hand. 
 
 After the key has been generated and the destination set on the map. The key can be sent 
 by email to registered scouts by a verified email account.  Once a scout enters in a key
 into the map game server a timer will be started and destination given. The end of the game
 scenerio will be when a device location matches the destination. if the device is connected
 to the server it will send the pdf file, if not connected it will halt the game and timer
 and wait until the devie is connected. Once it has been, the pdf will be sent to the device. 
 The pdf can be text and graphics but limited to a 5M size. 
 
 Each game:
    Time limited of up to 1 month. No less than 5 minutes. 
    A scout limit of 50 players.
    Destination has to be a place where the exhibitor has been while in the map app.
    A single PDF file from the exhibitor sent to the hosted map server.
    End game triggered when one of the scouts get to the destination and sends data back to server,then the server sends the pdf.
    End Game triggered by the exhibitor canceling the game.  
 
 
 [ ] Google map app test
 [ ] PDF Viewer app test
 [ ] Server setup to generate key
 [ ] Server setup to host pdf files. [no larger than 5M]
 [ ] Server setup to log in users.
 [ ] Server setup to specifiy Admin User - exhibitor or scout to each game.
 [ ] Server setup to use Google maps
 [ ] Server setup to get lat lon from map arrow location.
 [ ] Server set destination and KEY and time limit and end game scout who completed it in a mysql DB. 
  
 
