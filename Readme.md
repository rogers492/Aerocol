# Aerocol App Design

Corona provides a function to test the RGB colour at a point x,y on the display.
Documentation is [here](https://docs.coronalabs.com/api/event/colorSample/index.html#TOC)

## Initial User Stories:
### User Story #1 - Sample
- The User takes a photo of the sky with their phone.
- The User starts the Aerocol app.
- In the app, the User selects the photo from the phone gallery. The app displays it. **DE-RISK EARLY**
- The User taps the screen at the point they want the app to sample.  It is up to the user to tap on SKY rather than CLOUD.
- The app uses colorSample to retrieve the RGB value at the x,y tapped by the User.
- App does simple quality checks (is colour sample somewhere between blue and white?) and adds quality flag
- The app compares RGB at x,y against the RGB values of the standard colour swatches (stored constants).
- The app displays the closest swatch and other feedback.

### User Story #2 - Transmission
- User presses send button
- App asks send or cancel?
- App sends by preconfigured method: sms, email, ???

## Further User Stories:
### User Story #3 - Preferences
- User sets tx preferences: sms or email or ???

### User Story #4 - Calibration

## Product Backlog
### Sprint #1
[ ] In the app, the User selects the photo from the phone gallery. The app displays it. **DE-RISK EARLY**
### Sprint #2
[ ] The User taps the screen at the point they want the app to sample.  It is up to the user to tap on SKY rather than CLOUD.
[ ] The app uses colorSample to retrieve the RGB value at the x,y tapped by the User.
[ ] The app shows the RGB values retrieved
### Sprint #3
[ ] App sends by email

