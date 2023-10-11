# Scenario 1

## Application Type

### Decision

This app will be a **native** app on mobile platforms.

### Context and Considerations

* The app should run in offline mode and without a stable internet connection
* The app should send push notifications and make full integrated use of them
* The app should display product images of varying size and resolution, using system hardware to do so
* The app requires the use of several libraries for translation and consideration

### Rationale

The decision to make the app native to mobile platforms primarily stems from the first consideration, in which the app needs to be accessible offline and without an internet connection. Otherwise, while web/hybrid apps can make use of push notifications and image display considerations, integrated use of a mobile device's native libraries and features will streamline this far better.

## UI Framework

### Decision

This app will developed using **React Native**

#### Context and Considerations

* React Native is by far one of the most popular cross-platform UI frameworks, and is, as a result one of the most documented and flexible frameworks

## Backend Languages

### Decision

This app will make use of **Node.js** and **React.js** as its primary scripting and backend languages.

### Context and Considerations

* The application's User Interface will make use of React Native
* The application requires extensive user interaction and the ability to handle sevreal requests at once
* The application demands real-time server synchronization

### Rationale

The choice is clear for making use of **Node.js and React.js** as backend languages, as they are both powerful, server-oriented languages that facilitate real-time communication, data fetching and responsiveness between clients and servers. This should meet several business requirements relating to real-time server syncing, secure gateways and so forth.

## Permissions

### Decision

The app will request the following permissions:

* Location
* Notifications
* Photos and Videos
* Internet
* Nearby Devices

### Context and Considerations

* The application should track users' activities on the app, and will likely factor in their movement to stores and interactions with loyalty programs
* Notifications will be sent to uses whenever an order updates, new products arrive or exclusive offers arise
* The application, while able to function offline, will require some degree of network connectivity
* The app will display product images, which may be compressed and stored on the user's device for offline use.

## Data Storage

In order to support the app's needs, a database solution will likely be made use of, such as MySQL or Oracle. On the other hand, the app will have to make use of a client device's own storage to support offline functions and native image formatting solutions.

### Context and Considerations

* The retail company wishes to track behaviour, purchases and loyalty program functions
* As a retail application, deliveries, order histories, product inventories and similar have to be managed.

## Additional Frameworks

### Decision

The application will also make extensive use of services such as **PayPal**, **Google Analytics**, **Amazon Storage** and **Localization Services** amongst other, similar solutions.

### Context and Considerations

* The application will be internationally used, and localization will be necessary for reaching diverse groups
* The company wishes to track customer behaviour, spending patterns, loyalty and purchases to implement better performance and User Experience
* The app needs to be integrated with various payment gateways, with secure and convenient transactions

### Rationale

Despite meeting business requirements, these services will likely not be the only ones involved in the app's other connections. These are simply the most prominent and well-known names in the industry, and making use of them will vastly streamline the application's development.