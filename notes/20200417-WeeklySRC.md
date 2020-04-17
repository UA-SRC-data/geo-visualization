Ramona, Ken, Kate, Jiacheng, Monica, jdeck, Priyanka

Ken tells us about his make tutorial. He'll do a flipped classroom next week.

Ken will now give us an overview of frictionless data and then we'll talk about data loading process

https://frictionlessdata.io/ 

- Trying to create a way to describe data as "data packages"
  - can have multiple input files
  - create a json file that describes where resources come from, the format, what the fields are
    - by default is string type, but we can convert them to floating point
  - possibly documennt ontology in the data package
  - Might be a nice way to share SRC data other people
- Handle weird values you like "no standard given" in a numeric field
  - also "below limit of detection" versus zero... they're not the same meaninng
- Ken notes that the standardds column is not a measurement, it's a standard value
  - Monica explaisn that it's because its' the standards file
- Monica explaisn the "private" spreadsheet is named that because it shouldn't be uploadded wiht lat/long

API

- Usinng Let's Encrypt to get an HTTPS certificate
- We have the FastAPI but the data is missing the location information
  - Going to run the code with point-to-shape to use blockgroups
- Kate verifies we should be able to use the EJScreen data at blockgroups now
  - Ken says there may nont yet be a media (e.g. plants) for EJScreen yet
