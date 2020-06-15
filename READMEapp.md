# 05 Third-Party APIs: Work Day Scheduler

Application description:

This daily calendar let the user enter a new event on any of the input fields. When the user inputs an event and clicks on the 'Add event' button, the values will store in local storage and automatically return then in the same input field. This application is powered by the Moment.JS API and it's used to continuously display the current date and time. The time values are retrieved 12hr - strings, then are converted into military time to both create and assign each event block an unique number identifier. The background logic color codes all input fields red if an item is in the past, blue if it's in the present, and green if it's in the future.

