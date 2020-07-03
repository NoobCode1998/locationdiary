Covid Diary

This app is built using Flutter.

Record your location activities such as location data, people you met and places you've been. On launch, the user registers their name and phone number which acts as a unique identifier for the user. Once registered, the user is presented with a screen having the following three options:

    Add person or place to your list. This feature allows you to scan QR codes of other people using the app or QR of a place/vehicle that is already registered with the app.
    Check my visits This redirects you to a screen, where you can see the people/places and the auto recorded location data.
    Add this place This adds the current location to your travel history.

Salient Features

This app tracks location of the user continuously and adds it to your covid diary. When people meet, if X meets Y, X could scan QR in Y's phone and both of their diaries would be updated with required data. From the list of places visited, users can find that location on the map on click of a button (Google map opens with a marker at the selected location). This app automatically logs your current location data periodically even after the termination of the app.

Usage
Once logged in your name and phone number identifies you
A QR code is shown in your homepage from the time you first login. The data of this qe code is "p-Ee-r"+(your name). The string concatenated before your name helps the app to identify you as a person and not a place.
each time you go to a place You can mark the place youve been by

 1. Scan Qr code of the location 
            we assume most places(public) have the qr code registered.The Qr Code data has name of the place and a string "pLc" appended to its starting to identify it as public place
            
            
            
 2.Scan The Qr code of other users of the app
            once you scan somones QR code a mutual contact is added to both the peoples diaries .(if x scans Y  then both X's duary and Y's Diary shows that they've met )
            
            
            
 3.Automatically logging of location data for later usage.
