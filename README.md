#!/bin/bash

## What is the technical term for the code on Line 1 "shebang"
## What does it accomplish "which interpreter runs the script"

# ---------------------------- 
# chmod+x process.sh
# ----------------------------

##Explain lines 11 - 13. What are they and where are they used later in the script?

INPUT_FILE="input/fruits.txt" Storage the path to the input file
OUTPUT_DIR="output" stores the output the folder name
OUTPUT_FILE="$OUTPUT_DIR/fruits_processed.txt" stores the final output file path/ value becomes
@VARIABLE_NAME

mkdir -p "$OUTPUT_DIR"

# see if you can get the output on line 20 by intentionlly causing an error.
mkdir -p [SOUTHPUT-DIR]
if [ ! -f "$INPUT_FILE" ]; then
    echo "Error: Input file not found!"
    exit 1
fi

echo "Processing file..."

# 
while IFS= read -r line
do
    
    processed_line="PROCESSED: $(echo "$line" | tr '[:lower:]' '[:upper:]')"
