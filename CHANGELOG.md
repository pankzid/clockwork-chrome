1.4.1
- fixed a bug where numeric values were displayed as empty objects

1.4
- added views and emails tabs
- empty tabs are no longer shown
- improved compatibility when incomplete data is received

1.3.1
- log level is now specified as string by client, allowing any level names
- added support for custom headers on metadata requests specified by client via X-Clockwork-Header-NAME headers
- fixed non-string and object values not being pretty-printed correctly

1.2
- updated design for the new flatter dev tools look comming in Chrome 32
- json values in request data, logs, session and cookies now displayed as interactive elements similar to Chrome javascript console
- fixed compatibility with some older versions of the Clockwork php library
- fixed wrong order of the timeline events

1.1
- added support for custom Clockwork data uri (used for apps running in subdirs for example)

1.0
- released on Chrome Web Store! - https://chrome.google.com/webstore/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp
- added new standalone web app version - https://github.com/itsgoingd/clockwork-web
- changed extension logo

0.9.1
- added application routes tab
