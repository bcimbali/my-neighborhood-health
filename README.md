# My Neighborhood Health

## Check it out here:
https://obscure-tor-83881.herokuapp.com/

## The Why:
Are there toxic chemicals stored near where you live or work? If there are, are those chemicals being released to the air or water nearby? Would you like to find out?

We were curious (concerned). We understand, locating that information is very tricky. There are several different pages at the EPA that have this information but they are either tough to find or give the user too much detailed information. 

## The What:
This is an easy-to-use resource for people to search our map and find facilities working with toxic chemicals nearby their work or home. Once a facility is clicked, a pop-up window appears and gives a quick run-down of the facilities details. If the user wants to learn more about, say, particular chemicals or if the facility is in compliance with the EPA, they are linked directly to an EPA page for that particular resource. 

## Type of Info Available
* Name of TRI Facility
* List of toxic chemicals at site
* Direct links to Toxnet for each toxic chemical
* If the facility works with Carcinogenic chmicals
* Facility Compliance History
* Ability to check in as a neighbor of each site
* Count of users who have checked in as a concerned neighbor of each site

## Screenshot:
![My Neighborhood Health Screenshot](https://github.com/bcimbali/Responsive-Portfolio/blob/master/assets/images/my-neighborhood-health-screenshot.png?raw=true)

## How to Install and Run the App:

- Clone the repo
- Run `npm install` to get dependencies
- Run the `schema.sql` in your SQL client of choice
- Seed the database with the 2 csv files in the `data` folder
    - `chemical_info.csv`
    - `facility_info.CSV`
- Run `node server.js`
- Go to `localhost:8080` in your web browser


## Built With
- Node.js
- MySQL
- HTML
- CSS
- Bootstrap
- Google Maps API
- Data from TOXNET Web Service API
