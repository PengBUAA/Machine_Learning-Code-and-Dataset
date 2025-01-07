# Machine_Learning-Code_and_Dataset

The specific experimental data from the two sets of experiments have been made publicly available. Exp1 consists of data collected at the East Annex of the Library at Beihang University, further divided into real-time collected datasets and later collected datasets. Exp2 consists of data collected at the New Main Building at Beihang University.

Each dataset includes training and testing sets that have been processed, interpolated, and normalized. The input data consists of:

    Columns 1-3: Processed magnetic field strengths
    Column 4: Air pressure
    Columns 5 to the end: WiFi signal strengths from different addresses

The output data includes:

    Columns 1-3: Coordinates in the east, north, and vertical directions

Additionally, detailed data for each floor’s corridors, staircases, and elevators are provided, with the following structure:

    Column 1: Data point identifier
    Columns 2-4: Position coordinates
    Columns 5-7: Raw magnetic field strengths
    Columns 8-10: Acceleration data
    Column 11: Air pressure
    Columns 13 to the end: WiFi signal strengths from different addresses

