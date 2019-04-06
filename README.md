# Promise Project
 * Build a web app that displays a vertical Timeline of data like below.  The app should:

    * Have a NodeJS server that returns the structured data for the front end app.

    * Have a ReactJS front end that fetches that data and displays it.

    * Support multiple event types including
  
        1. Court Date
        2. Reminders for Court Dates
        3. Case Manager Appointments
        4. Client data being updated
    * Each event should be able to display whether it had been attended or not
    * Have a button that opens a form letting the user add a new item to the Timeline.
    * Sort by date, in descending order, clearly showing which items are in the future, and which have already passed, as in the image.

## Connecting ReactJS Frontend with NodeJs Backend
* Setting up a Back-end of the app using `express-generator`.
* Using `create-react-app` to scaffold a front-end Reactjs app.
* Using `axios` for cross-origin API calls
* Handling POST request on our server
* Using `express-fileupload`, a promise based library
* Lastly, connecting a Reactjs and Node.js
