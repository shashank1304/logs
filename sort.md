# Linux Sorting Commands
## Sorts lines alphabetically (A–Z)
    sort filename
## Reverse order (Z–A)
      sort -r filename
## Remove duplicate lines
      sort -u filename

# Numeric Sorting
## Sort numbers correctly (1, 2, 10 instead of 1, 10, 2)
       sort -n filemane
## Numeric + reverse order
      sort -nr filename
# Sorting by Columns
## Sort by 2nd column
         sort -k2 filename
## Sort by column 2, then column 1
         sort -k2,2 -k1,1 file.txt
## Sort CSV by 3rd column
       sort -t',' -k3 data.csv
