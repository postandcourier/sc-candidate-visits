# sc-candidate-visits
The Post and Courier is tracking visits to the South Carolina by known and presumptive candidates.

This is where the database will be kept and maintained. The format is geoJSON.

Each event corresponds to a scheduled or past event by presumptive candidates, as determined by Post and Courier reporters.

##Included Data

In addition to standard geoJSON geometry, the following feature data will be included for each event (where applicable):

Data              | key name      | type
------------------|---------------|---------
Candidate Name    | candidate     | string
Month             | month         | num
Date              | date          | num
Year              | year          | num
Description       | note          | string
P&C Coverage Link | storyurl      | string

Questions? Look for @jaspar on twitter.
