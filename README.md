# Awk Examples

This repository provides a collection of examples illustrating how to use Awk for text processing and data manipulation.

## Installation

### Linux
Awk is typically pre-installed on most Linux distributions. You can verify its installation by running `awk --version` in your terminal.

### Windows
For Windows users, this repository includes a Dockerfile to set up a Linux container where Awk is available.

**Steps to create and run the Docker container:**
1. Open PowerShell.
2. Navigate to the directory containing the Dockerfile.
3. Run the provided PowerShell script to build and execute the Docker container:
```powershell
./rundocker.ps1
```


## Getting Started

The src folder contains sample scripts and data files for testing. You can generate CSV files using Excel or similar programs and then process them with Awk scripts.

To run an Awk script, navigate to the directory containing your script and execute it using the command below:
```bash
awk -f script_name.awk input_file.csv
```
    
You can also use the premade scripts:
```bash
console.awk
```