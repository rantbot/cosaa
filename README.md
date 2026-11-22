# Camp Oyo Staff & Alumni Association

This site shows the members app on the association's own web address.
The app itself runs on Google Apps Script and stores members in a private
Google Sheet. Nothing private is in this repository.

It can also be added to a phone's home screen. Each time the app opens with
signal, it saves a copy of the roster on that device, so people can still be
looked up when there's no signal. That copy is look-up only.

To point it at a different app address, change `APP_URL` in `index.html`.
