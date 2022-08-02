Kate, Monica, Alma, Jackson

- Discussion of database access with CALS IT continues. Both Kate and Monica agree that having CALS maintain it would be the consistent option that fits the workflow.

- Alma shows alternative sources of diabetes data (e.g., NHANES, ADHS)
  - Alma and Monica point out that it's not always statistically significant in NHANES
    - They only picked 15 random counties across the US to sample from, not sure any are in Arizona
    - Would be cool to correlate this data in another project so we can compare to nation-wide
  - Monica asks about the ADHS
    - Alma says they have a 2019 dataset 
    - Monica asks if it's limited to hospitalizations
    - The resolution is only state-wide
    - Alma says ADHS is still the stronger dataset but it would only be state
    - They go searching to "vital statistics" in the website
      - Can find diabetes as 'cause of death' (death certificates) divided by age, gender, area (e.g., rural), ethnicity
        - Monica wonders if we can reach out to the contact person
        - See if we can get more pointers since BFRS is difficult, also see if they have CSV format and/or county data

- Alma brings up the lat/long data that Jackson gave (with thanks!) and then asks about the data vs. Frontiers paper
  - She points out the "Explore HPSAs" categories and verifies with Monica

- Voting website didn't respond, can we scrape from the website where the map points are
  - Jackson seems to believe he'll be able to do that. 

- Jackson will now talk about how far he's gotten with the UI
  - WHERE/WHO still are just stubs
  - First column now links directly to the ontology!
    - You can select something and then it checks the ontologies for all child terms and figures out which ones exist
      - Kate asks about performance given the size of the ontolog (it's not that big)
        - He says it's only "Age" that takes a while to load (also Disability/Status) so maybe we can preprocess it
          - Also "Age" is more of a filter so we could remove it and turn it into a filter
  - Notes the direct search only work on ACS and EJSCREEN because their IDs are linked between database and ontology
  - He also shows the contaminents, to remind folks how that works but it does not load the appropriate thing yet because the concentration data in the database is not formatted the way we want it to be
    - By "not formatted well" he means the different mediums are listed under the same variable -- so we should update the database
  - Monica says "This is great progress"
  - Map colors still have a bug in overlap of range

- We start to discuss again what's a "topic" versus "filter"
  - Kate suggests we decide "topics" are based on the tables in the Frontiers paper
    - Monica refines it based on question
    - Maybe the rightmost column in Tables 1 and 2 for the measure, and the left most column for the Topic
      - Okay so Topic is "Data Description" (leftmost column) and Measure is "Variable Categories" (rightmost column) and then pull from ontology becomes the filters

- Jackson asks about employment vs. labor force status
  - Monica thinks labor force status is the categories of employment (e.g., mining) and employment is the counts
    - Might need to rename them as employment status and employment type
