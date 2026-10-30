## XX.XX.XX

* Added a "Device ID" option to the init action for setting a custom device ID
* Added a "Max Key Length" option to the init action to limit key length

## 25.4.0

* ! Minor Breaking Change ! SDK now supports Server Configuration feature and it is enabled by default. Changes made on SDK Manager > SDK Configuration on your server will * affect SDK behavior directly
 
* Added support for Survey, NPS and Rating Feedback Widgets with a new action
* Added support for Journeys with a new option during init action
* Added a new action for refreshing Content zone if Journeys are enabled
* Added automatic backoff mechanism which delays sending requests if server seems busy
* Added timezone support for server
 
* Improved orientation reporting precision
* Improved error handler to include script loading issues
 
* Default request method is now set to "POST"

* Updated underlying SDK version to 25.4.1

## 23.12.2

* Added `sum`, `count` and `duration` to events
* Added event tests

## 23.12.1

* Added automatic link tracking
* Updating underlying SDK version to 23.12.6

## 23.12.0

* Initial release with automatic tracking and recording events