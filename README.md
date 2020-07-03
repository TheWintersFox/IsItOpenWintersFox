# [Is It open?](https://thadkingcole.github.io/is_it_open)

<img src="./assets/images/screenshot.png">

## KabanFlowTracking

https://github.com/thadkingcole/is_it_open/projects/1


## Table of Contents

- [Description](#Description)
    - [Country](#Country)
    - [State](#State)
    - [Country](#county)
    - [Yelp](#Yelp-Fusion-API)
- [User Story](#user-story)
- [Deployed Application](#deployed-application)
- [Validation Link](#Validation-link)
- [References](#references)
- [Collaborators](#collaborators)

## Description

With the current public health situation, people want to go outside, but it is difficult to find places that are open. This app will curate a list of restaurants, bars, and parks that are listed as open powered by a [YelpFusion API](https://www.yelp.com/developers/documentation/v3), while also giving the user the current number of covid19 cases in the search location. The app can grab data by multiple criteria.

Two different covid APIs were used to return the following data on the app. [Covid-19 Statistics](https://rapidapi.com/axisbits-axisbits-default/api/COVID-19%20Statistics) was used to gather information down to the county for locations within the United States. [Covid-19 Data](https://rapidapi.com/Gramzivi/api/COVID-19%20data) was used to gather information for the country when the user searched outside the United States.

### Country

(if outside the US)

  - Total Confirmed Cases
  - Total Critical Cases
  - Total Deaths
  - Total Recovered

### State

(US only)

  - Display when the last set of data was pulled from date and time
  - Total active cases
  - New active cases since the previous day
  - Total confirmed Cases
  - New confirmed cases since the previous day
  - Total deaths
  - New deaths since the previous day
  - Fatality rate in a percent

### County

(US only)

 - Display when the last set of data was pulled from date and time
 - New cases since the previous day
 - Total Deaths
 - New deaths since the previous day
 
 ### Yelp Fusion API

The yelp API will pull data under the selected checkbox, as well as the mile radius from the location the user specified.  The yelp data will display 

- Restaurants, Bars, and Parks
- It will populate individual locations based on the checkbox the user selected in the classes listed above
- It will display the address of the businesses or parks 
- It will display the phone number of the businesses or parks
- It will display the yelp icon for all data originating from yelp as well as the average score of all reviews displayed in the classic yelp out of 5 star format
- It will display the open or closed status of the business, if the business hasn't updated its information recently for the open or closed status it will not display as open or closed and will be left blank

For both the yelp API as well as the corresponding COVID data the user can enter a City, state, address, zipcode to display relevant information. If the user does not choose one of the following (restaurant, bar, or park) it will tell the user to select at least one by the use of a modal.

[back to top](#is-it-open)

## User Story

As a person suffering from cabin-fever, I want a list of open restaurants/locations and current covid19 stats to decide where I should go outside.  I can then evaluate the amount of cases in my current county and state and make an informed decision if it is safe to venture out to the local restaurants or bars. If I am interested in seeing data about other places around the world, I will be able to enter a country name, state, address, or zipcode to display information about said places.

[back to top](#is-it-open)

## Deployed application

- Deployed Website: <https://thadkingcole.github.io/is_it_open/>

- Github Repo: <https://github.com/thadkingcole/is_it_open>

[![Deployed Application Screenshot](./assets/images/DeployedApp.gif)](https://thadkingcole.github.io/is_it_open)

[back to top](#is-it-open)

## Validation Link

- [CSS Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fthadkingcole.github.io%2Fis_it_open%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

- [Nu HTML Checker](https://validator.w3.org/nu/?doc=https%3A%2F%2Fthadkingcole.github.io%2Fis_it_open%2F)

[back to top](#is-it-open)

## References

- Favicon: <https://www.flaticon.com/authors/vitaly-gorbachev>
- Covid-19 Data API: <https://rapidapi.com/Gramzivi/api/COVID-19%20data>
- Covid-19 Statistics API: <https://rapidapi.com/axisbits-axisbits-default/api/COVID-19%20Statistics>
- Yelp Fusion API: <https://www.yelp.com/developers/documentation/v3>

[back to top](#is-it-open)

## Collaborators

- [Thad](https://github.com/thadkingcole)
- [Everett](https://github.com/diuguide)
- [Luke](https://github.com/TheWintersFox)

[back to top](#is-it-open)
