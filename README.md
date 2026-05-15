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

echo "I need to pass this class. $(weaponofchoice), with an original." >> survive.txt

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
#Moving Selected Files

#Listing everything in the directory, with some flags. 

ls -lta

#Copying
cp -v survive.txt $BACKUP_DIR/

#Moving Selected Files

mv -v survive.txt $BACKUP_DIR/

#Removing Files and Directories

rm -v $BACKUP_DIR/survive.txt

mv -v processed_line.txt $BACKUP_DIR/

#Processed output is also placed into the archive    
processed_line="PROCESSED: $(echo "$line" | tr '[:lower:]' '[:upper:]')"
archived_line="ARCHIVED: $(echo "$line" | tr '[:lower:]' '[:upper:]')"

#Archive the processed line    
echo "$processed_line" >> "$OUTPUT_FILE"
echo "$archived_line" >> "$ARCHIVE_FILE"

echo "Done!"
echo "Processed lines have been saved to: $OUTPUT_FILE"
echo "Processed lines have been saved to: $ARCHIVE_FILE"

cat final_report.txt

