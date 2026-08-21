# Worklog

## Week 1

- (Thursday 13.08.2026) (0.5 Hours) Project initial setup
- (Friday 14.08.2026) (1.0 Hours) Implemented a first test for `thematic breaks` and implemented the necessary logic for that test

## Week 2

- (Monday 17.08.2026) (1.5 Hours) Read the common markdown specs, changed the way to parse the input as common markdown is not context free.
- (Tuesday 18.08.2026) (1 Hour) Add Handling of atx-headers to the lexer.
- (Thursday 20.08.2026) (1.5 Hours) Changed the resulting type of tokens into a discriminated union type, to have more information about the token at a later time in the parsing process.
- (Friday 21.08.2026) (1.5 Hours) Improving the lexer by adding metadata like length, representation, start and end position of the token. Tests were adapted to include this new metadata information.
