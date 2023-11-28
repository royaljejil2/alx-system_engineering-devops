# Regular Expressions Usage in Oniguruma Library

This project highlights the application of regular expressions specifically tailored for the Oniguruma library.

## Task Summary :page_with_curl:

_Note: Each Ruby script within the project executes regular expression matching based on a command-line argument._

### 0. Basic Match for 'Holberton'
- [0-simply_match_holberton.rb](./0-simply_match_holberton.rb): Ruby script that matches the regular expression `School`.

### 1. Repetition Token #0
- [1-repetition_token_0.rb](./1-repetition_token_0.rb): Ruby script that matches the regular expression `hbn` with 2-5 `t`'s occurring between `hb` and `n`.

### 2. Repetition Token #1
- [2-repetition_token_1.rb](./2-repetition_token_1.rb): Ruby script that matches the regular expression `hn` with either 0 or 1 occurrence of `b` and 0 or 1 occurrence of `t` between `h` and `n`.

### 3. Repetition Token #2
- [3-repetition_token_2.rb](./3-repetition_token_2.rb): Ruby script that matches the regular expression `hbn` with 1 or more `t`'s found between `hb` and `n`.

### 4. Repetition Token #3
- [4-repetition_token_3.rb](./4-repetition_token_3.rb): Ruby script that matches the regular expression `hbn` with 0 or more `t`'s between `hb` and `n`.

### 5. Partial Match for HBTN
- [5-beginning_and_end.rb](./5-beginning_and_end.rb): Ruby script that matches a regular expression starting with `h`, ending with `n`, and having any single character in between.

### 6. Call me maybe
- [6-phone_number.rb](./6-phone_number.rb): Ruby script that matches a regular expression representing a 10-digit phone number.

### 7. Uppercase Expression
- [7-OMG_WHY_ARE_YOU_SHOUTING.rb](./7-OMG_WHY_ARE_YOU_SHOUTING.rb): Ruby script that matches regular expressions for uppercase letters.

### 8. TextMe Analysis
- [100-textme.rb](./100-textme.rb): Ruby script that conducts statistical analysis on TextMe app text message transactions.
  - Output format: `[SENDER],[RECEIVER],[FLAGS]`
    - `[SENDER]`: Sender's phone number or name (including country code if applicable).
    - `[RECEIVER]`: Receiver's phone number or name (including country code if applicable).
    - `[FLAGS]`: Flags utilized in the message.
