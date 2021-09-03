# CSV Combiner

The script `combine_csv.py` takes an input of CSV files and generates a combined output CSV with the desired schema.

## Run the program

- This script assumes you have Python installed on your machine
1. Clone this repository to your personal GitHub account.
2. Open the Zebra directory.
3. Place input csv files in the input folder.
4. In your terminal run `python combine_csv.py`. Make sure you are in the 'Zebra' directory you cloned.
5. Check the output folder to see the combined csv output file.

## Run Tests
1. In your terminal run `python ./tests/testCombine.py`.
The test checks if given two test input csv files the expected combined output is generated in its DataFrame format.

## Additional Thoughts
1. Additional tests could be written for the function which creates directories.
2. The test compares the equality of two DataFrame objects instead of the actual csv files.
3. Had testing been implemented using pytest - more thorough testing and mock data could have been created.