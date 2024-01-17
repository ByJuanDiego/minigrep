# Mini-grep

Command line application for searching string patterns in a file.

Syntax:
```
IGNORE_CASE=[option] cargo run -- [pattern] [file]
```

Example:

```shell
IGNORE_CASE=0 cargo run -- "Moby Dick!" book.txt
```

Output:

```
seen—Moby Dick—Moby Dick!”
Moby Dick!”
deathful whaleboat’s bow—Death to Moby Dick! God hunt us all, if we do
“‘Moby Dick!’ cried Don Sebastian; ‘St. Dominic! Sir sailor, but do
Moby Dick!”
“Aye, breach your last to the sun, Moby Dick!” cried Ahab, “thy hour
“Forehead to forehead I meet thee, this third time, Moby Dick! On deck
```
