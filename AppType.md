## Application Type

### Status

Proposed.

### Decision

This app will be a **native** app on mobile platforms.

### Context and Considerations

* The app should run in offline mode and without a stable internet connection
* The app should send push notifications and make full integrated use of them
* The app should display product images of varying size and resolution, using system hardware to do so
* The app requires the use of several libraries for translation and consideration

### Rationale and consequences

The decision to make the app native to mobile platforms primarily stems from the first consideration, in which the app needs to be accessible offline and without an internet connection. Otherwise, while web/hybrid apps can make use of push notifications and image display considerations, integrated use of a mobile device's native libraries and features will streamline this far better. As a native application, the implementation of its business requirements will be made considerably easier and simpler.




