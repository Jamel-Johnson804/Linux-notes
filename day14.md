#Day 14 - Searching Files using grep

## Commands used

nano system.log
grep ERROR system.log
grep WARNING system.log
grep INFO system.log
grep -c ERROR system.log
grep -n ERROR system.log
grep -i ERROR system.log

## What I Did

-Created a sample log file
-searched log for error/warning/information messages
-Counted the number of error messages
-Displayed line numbers for matching results
-Performed a case-insensitive search

## What I LEarned
grep
 -searches text files for specific words or pattern
grep ERROR
 -displays every line containing "ERROR"
grep -c
 -Counts how many matching lines exist
grep -n
 -Shows lines numbers with the matching results
grep -i
 -ignores uppercase and lowercase difference
## Screenshots
![grep](screenshots/grep.png)
