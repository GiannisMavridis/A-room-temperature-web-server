We use an Arduino Uno with an Ethernet shield in order to build a
temperature web server.A LM35 temperature sensor,which is connected 
with the Arduino, mesasures the room's temperature. 
The server listens for clients' requests(the clients are web browsers)
and then sends them back the room's temperature in a simple HTML page.
Finally,the browser displays the message "The room temperarue is X *C" ,
where X is the room's temperature now. 

--Android app that displays the room's temperature in real time--
we can also build a simple android app that displays the room's temperature.
Just create an Activity and include a WebView in its layout.Inside the activity's
code, link the webview to the arduino 's IP adress with the following statement
 webview.loadUrl("http:// arduino's IP here");
 
 
