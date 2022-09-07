Version
- Node v8.12.0
- NPM 6.4.1
Run 
- 'npm i' to install dependencies
- 'npm run index' to generate output 
- 'npm run test' to run test cases

## Specs

### League Rules
Rankings are determined by points. Points are awarded to teams as follows:
- A win is worth 3 points
- A draw is worth 1 point
- A loss is worth 0 points

### Input
The expected input is a text file (see `input.txt` for valid example input)

### Output
The expected output is a text file. Each time the software reaches the end of a complete match day, it should output the results of that match day. A complete match day consists of three games.

Output format:
- output should be grouped into match days, with an empty line at the end
- each match day should have a header showing "Matchday x", where x is the number of the match day (starting with 1)
- the three teams with the highest aggregate point totals should be listed in order from most to least points. If multiple teams have the same point total, they should be ordered alphabetically

see `test/fixtures/formattedOutput.txt` for valid example output
