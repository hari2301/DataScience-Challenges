# About

The aim of the challenge is to predict the cab fare using the given dataset. The dataset consists of 3 CSV files:

    TRAIN.csv
    TEST.csv
    sample_submission.csv

TRAIN.csv consists of 9 attributes:

    index
    time_stamp - epoch time (in seconds) when the cab was booked
    cab_provider - company (Uber/Lyft)
    source - the starting point of the cab ride
    destination - the destination of the cab ride
    distance - the distance between source and destination
    surge_multiplier - multiplier by which price increased
    cab_type - the type of cab (Uber Pool, Uber XL, etc. )
    fare - cab fare in USD (Target Attribute)
