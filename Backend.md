## Backend Languages

### Status

Proposed.

### Decision

This app will make use of **Node.js** as its primary scripting and backend languages.

### Context and Considerations

* The application's User Interface will make use of React Native
* The application requires extensive user interaction and the ability to handle sevreal requests at once
* The application demands real-time server synchronization

### Rationale and consequences

The choice is clear for making use of **Node.js** as backend language, as it is a powerful, server-oriented language that facilitate real-time communication, data fetching and responsiveness between clients and servers. This should meet several business requirements relating to real-time server syncing, secure gateways and so forth. As a result, extensive use of Node.js will allow backend commications to become more robust and capable. This allows the application to easily meet the data syncing, security and other business requirements.