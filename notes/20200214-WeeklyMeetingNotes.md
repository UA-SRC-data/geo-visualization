Ken has Census data in an sqlite database currently.

- Can aggregate by city right now
  - When we aggregate less aggressively, there will be a lot more
- This isn't all data from all time
- Monica wonders if we can do queries with public health terms... for example, "sensitive vulnerable populations" partially from EJ screening tool:
  - Children under 5, People above 65, Women of pregnant age, don't speak English, don't have education beyond high school
  - May want from Census rather than EJ screening
    - EJ screening might have some data census doesn't have though... has environmental exposure AND then calculates a risk
    - We may have to sit down and select fields
      - Student to walk us through the data next week maybe
        - Let's look at EJ screening tool next week and figure out what we want to use even without the student
        - Monica will make a table
          - Let's not do that yet because we might find things together
- Yavapai, Cochise, Apache, Greenlee is where we have Gardenroots data, so we should start there.
- Chris' data is Colorado School of Mines and 18k datapoints but we're not using Colorado stuff
- Also care about start-date/end-date
  - Ken can show things on a map with this (wonder how this interfaces with Jiacheng)
- Ken also has an API (FastAPI, Swagger) and has type hints (misheard as tight-pants, keep in mind for later enunciation)
  - So this is going to help us filter and query
  - And get request URLs so perhaps we can use this in the vis
  - He can build more of this from the mongoDB
- We still believe CALS will serve internal use case but CyVerse may also host with budget



- Questions/Data sources?
  - Priyanka has an in-progress data source
  - Monica suggests 0 to 5 cm for the GardenRoots data
    - email forthcoming
  - Monica also has geochem data and biowater data so that's everything for the internal
