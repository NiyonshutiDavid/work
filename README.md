# Unique Integer Processor

## Overview
The Unique Integer Processor is a Python script designed to process text files containing integer values, identify unique integers within a specific range, and output sorted unique integers to a new file. This tool is useful for tasks where you need to filter and sort unique integers from input data sets.

## Features
- Processes text files containing integer values.
- Identifies unique integers within the range of -1023 to 1023.
- Outputs sorted unique integers to a new file.
- Utilizes bubble sort for sorting unique integers.
- Provides basic error handling for invalid input lines and out-of-range integers.

## Usage
1. Ensure you have Python installed on your system.
2. Clone or download the repository containing the Unique Integer Processor script.
3. Navigate to the directory containing the script in your terminal or command prompt.

### Running the Script
Execute the script using the following command:

1. Clone the repository
```bash
git clone https://github.com/NiyonshutiDavid/work.git
```
2. Navigate to the directory
```bash
cd work/
```
3. Run the executable file and change the permissions
```bash
chmod +x uniqueIntProcessor.py
```

```bash
python uniqueIntProcessor.py
```

### Input and Output
- **Input Files**: Place the text files containing integer values in the specified input folder.
- **Output Files**: The script will generate output files with sorted unique integers in the specified output folder.

### Example
Suppose you have the following input files:
- `input1.txt`
- `input2.txt`

After running the script, it will process each input file, identify unique integers, sort them, and create corresponding output files:
- `input1.txt_results.txt`
- `input2.txt_results.txt`

## Dependencies
- Python 3.x
- Standard Python libraries: os, time

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the GitHub repository.

## Author
David Niyonshuti

----------------------------------------------------------------------------------------------------------------------------------------------------------------
