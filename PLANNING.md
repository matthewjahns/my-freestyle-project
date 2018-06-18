# Project Planning

## Problem Statement

### Primary User

Movie-goers in the US looking for daily movie listings for nearby theaters.

### User Needs

The user needs an accurate listing of movie showtimes for nearby theaters, including directory information for each theater. This application aims to simplify the process for obtaining such information, reducing the steps required for using available applications or websites for the problem and without the intrusion of advertisements.

### As-is Process

For web browser:

1. Open up the browser and visit the URL for a movie listing site (for example, Fandango).

2. Input a zip code into the search bar.

3. Navigate to correct date in the top menu.

4. Scroll to the desired listing.

For mobile app:

1. Open the application.

  *Possible additional step: Enter a zip code or turn on location sharing for the app.

2. Select the "Theaters" tab at the bottom of the screen.

3. Scroll through the list of theaters and click on a theater to see it's listing of movie showtimes.

### To-be Process

1. Run the script.

2. When prompted, enter a zip code and date.

3. Receive showtimes from nearby theaters for that date.

## Information Requirements

### Information Inputs

The user will be prompted for the following inputs:

1. API key (if needed)
2. Zip code
3. Date for showtimes

### Information Outputs

Program outputs:

1. The application will output a listing of movie showtimes by theater for the date input by the user, in the proximity of the zip code input by the user, in the command prompt.

2. A csv file containing the showtimes for the most recent search.

## Technology Requirements

### APIs and Web Service Requirements

This application may utilize the Fandango API (https://developer.fandango.com/)

API documents are available here (registration required): https://developer.fandango.com/docs

### Python Package Requirements
The application may require the use of the following packages:

- requests (for web requests to the Fandango API)
- tkinter (may create a GUI for user inputs)
- pytest (for testing)

The application will likely also utilize the following modules:

- csv
- json
- os
- datetime
- pdb (for testing)

### Hardware Requirements

The application is designed to run locally through the command prompt, though it requires a live internet connection to successfully output listings.
