# iostoawsiot

This project allows to send device sensor information, such gps coordinates and accelerometer as an example from an iOS device just using a web browser.

The index.html can be running in any server with https enabled and the page can be loaded from the iOS device by typing https://server.

In this initial version and for the sake of simplicity as typing long text in a mobile device can be difficult, the required parameters for cognito and AWS IoT core have to be hardcoded in the html. Only the mqtt topic has to be entered in the html form.


