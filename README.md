# Quantox

## Word Frequencies

Write a program that determines the frequency of each word in a text.
You can either read the data from the sample file, read it as user input, or just paste the text inside the code.

Datasets that can be used are in this repository.

The generated output should look like this:

[](output.png)

You should print just the top 50 used words, along with their frequencies.

Considerations:

- "Word", "word", "WORD" should all be counted as the same word
- Don’t count spaces, tabs and other whitespace characters
- Don’t count special characters such as quotes, periods, colons etc.
- Don’t count numbers

Goal:

- Notice that each word's frequency is approximately inversly equal to it's rank
  - Second most used word appears approximately half as often as the first most used word
  - Third most used word appears approximately third as often as the first most used word
  - Etc.
- Why? Magic! See more at https://www.youtube.com/watch?v=fCn8zs912OE

[](screenshot.png)
