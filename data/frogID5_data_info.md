METADATA of the FrogID dataset (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7040047/)

Sorting the data for my purposes(FOR_ME):
X = contains all the same values / irrelevant information
O = important information

| COLUMN_NAME                     | FOR_ME | METADATA_DESCRIPTION                                                       |
|---------------------------------|--------|----------------------------------------------------------------------------|
| datasetName                     | X      | FrogID                                                                     |
| basisOfRecord                   | X      | Occurrence                                                                 |
| dataGeneralizations             | X      | Highlights the geoprivacy options that were implemented                    |
| occurrenceID                    |  O     | Unique ID for each record in the dataset                                   |
| sex                             | X      | Male frogs are being recorded                                              |
| lifestage                       | X      | Adult frogs are recorded in FrogID                                         |
| behavior                        | X      | Only calling frogs are entered into the FrogID database                    |
| samplingProtocol                | X      | Call recording                                                             |
| country                         | X      | Australia                                                                  |
| machineObservation              | X      | An occurrence record based on an audio recording                           |
| eventID                         |  O     | Refers to the submission id – one submission can have more than one record |
| decimalLatitude                 |  O     | Latitude                                                                   |
| decimalLongitude                |  O     | Longitude                                                                  |
| scientificName                  |  O     | Species name (Genus species).                                              |
| eventDate                       |  O     | Date in year-month-day format                                              |
| eventTime                       |  O     | Time the recording was taken                                               |
| coordinateUncertaintyInMeters   |  O     | A measure of the gps accuracy, measured in meters. See notes in methods    |
| geoprivacy                      |  O     | Indicates whether the record is included and/or coordinates are buffered   |
| recordedBy                      |  O     | Unique user id                                                             |
| stateProvince                   |  O     | Australian state of the record                                             |
| modified                        | X      | The date the record was last updated                                       |

Dataset download location: https://www.frogid.net.au/explore