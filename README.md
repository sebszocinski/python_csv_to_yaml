# Python &mdash; YAML Generator
Generate YAML files from rows inside a CSV

## Requirements
- OSX
- Python

## Usage
1. Create a `data.csv` file with all the data you wish to add to your yaml files.
⋅⋅* A sample `data.csv` file has been included for testing.
2. Run `python generate.py` in your terminal.
3. `.yaml` files will be generated and saved inside a `/yaml` folder.

## Note
- Make sure the first row contains the columns heading as this will be used in your yaml.
- The last cell in your `.yaml` will be used as the filename and also be included in the yaml data.

### Credits
Credits go to [hfionte](https://github.com/hfionte/csv_to_yaml) for the original script.
