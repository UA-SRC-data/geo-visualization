Ramona, Raina, Monica, Kate, Ken, Priyanka, Jiacheng, Biaca

Ken Data-Update, Data-Types

- src.cals.arizona.edu now live!
  - CALS VM provisioned
  - We could get a domain name if we wanted at like GoDaddy or whatever
  - Mostly the EJScreen data, workinng on USGS data
    - Needs to move geographic point to census block
    - There might be other weird boundaries
  - Colorado School of Mines Data has insect counts
    - Has them at stations
    - Small bug when you don't fill out all the fields
    - Working on disgusting spreadsheet into database
  - FastAPI to get datasets in JSON
    - CSM is the first thing created which was a generic way of the Colorado data
    - EJScreen end points include the variable definitions and the measurements
      - So now we have a way to create GET strings and an interface to test them out
- Ramona suggests bringing in the GardenRoots data next
- https://github.com/UA-SRC-data/data_loaders/tree/master/point2census
  - This will changeg a lat/long to a block group

Monica update on GardenRoots Data

- Now with all the plant data
- So has both soil and plant... there is some drinking water
- existing vis at GardenRoots -> Community Status -> Soil
  - Oh that's innteresting, just shows dot chart, jittered in one direction
  - Draws a green line across the standard
- In google drive:
  - standards folder with the standard
    - color === agency name/type of standard
      - might want to be consistennt with GardenRoots here?
  - private is the true data without the exact location but she has the lat/long elsewhere
- New data from Pinal/Gila counties
