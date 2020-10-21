# HW6-Weather-Dash
Pseudocode HTML:
 <!-- Bootstrap -->
 <!-- FontAwesome -->
 <!-- Style CSS -->
 <!-- Jumbotron to display the City name upon search -->
 <!-- Main container for webpage content -->
 <!-- Left side content with city search box and appended cities -->
 <!-- fontawesome magnifying glass -->
 <!-- list of prior searched cities -->
 <!-- clear storage button -->
 <!-- Right side content showing current weather and five day forecast displays on search -->
 <!-- Current weather displayed on top -->
  <!-- Five day forecast below the current weather -->
Psuedocode javascript:
// Set global variables, including Open Weather Maps API Key
// Function to get and display the current conditions on Open Weather Maps
// Obtain city name from the search box
// Set the queryURL to fetch from API using weather search - added units=imperial to fix
// Save city to local storage
// Create icon for the current weather using Open Weather Maps
// Offset UTC timezone - using moment.js
// Render cities list
// Obtain the 5day forecast for the searched city
// Set the header text to the found city name
// HTML for the results of search
// Append the results to the DOM
// Get the latitude and longitude for the UV search from Open Weather Maps API
// API solution for Cross-origin resource sharing
// Fetch the UV information and build the color display for the UV index
// Function to obtain the five day forecast and display to HTML
// Set up URL for API search using forecast search
// Fetch from API
// HTML template
// Loop over the 5 day forecast and build the template HTML using UTC offset and Open Weather Map icon
// Only displaying mid-day forecasts
// Build the HTML template
// Append the five-day forecast to the DOM
// Function to save the city to localStorage
// Check if City exists in local storage
// Save to localStorage if city is new
// Render the list of searched cities
// If localStorage is empty
// Build key of last city written to localStorage
// Set search input to last city searched
// Append stored cities to page
// Set to lastCity if currentCity not set
// Set button class to active for currentCity
// Append city to page
// Add a "clear" button to page if there is a cities list
// New city search button event listener
// Old searched cities buttons event listener
// Clear old searched cities from localStorage event listener
// Render the searched cities
// Get the current conditions (which also calls the five day forecast)

<!--CSS Pseudocode-->
/* Styles for website */
/* Header styling */
/* h1 style for city name */
/*Jumbotron padding and border */
/* City Search width */
/* fontawesome magnifying glass icon */
/*Current weather padding */
/* clear storage below list of cities */
/* Weather card styling */
/* UV coloring scheme for UV display */
/* Media queries */







