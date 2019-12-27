# Resume-Parser

This is a bash script to automatically order resumes by certain keywords and its associated point system.  The bash script should be named "HR_sorter", and read a file called "input.txt".  The "input.txt" file will have a keyword and a numerical weight on each line (separated by a space).  The ordering of the resumes by keywords should be based on a total score, which is the sum of the score for each keyword. Resumes will be simple ASCII-encoded text files (with random extensions) in a subdirectory called "submissions".  

The output of the "HR_sorter" script should show on each line the filename of the resume and total score of the resume, sorted by the 
total score (with higher scores being first).

- Resumes are in the "submissions" folder
- "HR_sorter" script in the top folder
- Keywords and assoicated weights are in "input.txt"

*Note: This script ignores cases when counting word matches.  Words "match" even if they appear 
in other words (e.g., plurals count).  Look at the -o option to grep.

## To Run
  1)     ./HR_sorter

## Example Output
  
