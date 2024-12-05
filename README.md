# React Router DOM: Missing Route Bug

This repository demonstrates a common error in React Router DOM v6 where a route is missing for a specific path. This leads to the application rendering nothing or displaying a 'not found' message when attempting to navigate to the missing route. 

## Bug Description
The App.js file is missing a route for the '/contact' path. When a user navigates to '/contact', the application will not render the Contact component as expected.  This issue happens because the router doesn't know which component to render for that specific path.