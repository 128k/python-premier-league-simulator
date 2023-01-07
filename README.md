# Premier League Simulator

This Python script simulates a full season of the Premier League and outputs all scores for each week and a final league table. It allows you to adjust the bias scores for each team to influence the outcome of the matches.

## Usage

To use the script, simply run it using a Python interpreter. It will generate random scores for each match and print out the final league table. You can adjust the bias scores for each team by modifying the values in the team_bias dictionary.

## Example Output

Here is an example of the output from the script:

```python
Week 1:
  Arsenal 2 - 3 Man City
  Aston Villa 1 - 1 Norwich
  Brentford 2 - 2 Crystal Palace
  Brighton 1 - 0 Watford
  Burnley 1 - 1 Southampton
  Chelsea 3 - 0 Tottenham
  Everton 1 - 2 Wolves
  Leeds 2 - 1 Leicester
  Liverpool 3 - 1 Newcastle
  Man Utd 2 - 2 West Ham

Week 2:
  Arsenal 1 - 2 Liverpool
  Aston Villa 1 - 2 Chelsea
  Brentford 1 - 2 Man Utd
  Brighton 0 - 2 Man City
  Burnley 1 - 3 Leicester
  Crystal Palace 2 - 2 Southampton
  Everton 2 - 2 Tottenham
  Leeds 0 - 2 Newcastle
  Norwich 1 - 2 West Ham
  Watford 1 - 1 Wolves

...

Final League Table:
Team       Points
Liverpool  104
Man City   93
Chelsea    84
Man Utd    81
Leicester  74
Tottenham  69
Wolves     66
Everton    64
Leeds      60
Arsenal    59
Crystal Palace 59
Brighton   58
Burnley    57
Southampton 57
Newcastle  55
Brentford  53
Norwich    51
Aston Villa 48
Watford    46
West Ham   44
```
