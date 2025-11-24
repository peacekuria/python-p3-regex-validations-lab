# RegEx Validations Lab

## Learning Goals

- Validate that strings match specific patterns using regular expressions.
- Search for strings that match specific patterns using regular expressions.

***

## Key Vocab

- **Regular Expression**: a sequence of characters used to search for a pattern
inside of a string.
- **Pattern**: a description of sequences of characters that share certain
traits with one another. Sequences do not need to be the same length or share
any common characters to pattern match. Also called a **filter**.

***

## Instructions

This is a **test-driven lab** focused on building regular expressions that match valid inputs and reject invalid ones. You will work in `lib/regex.py` to complete this lab.

### Setup

- Run `pipenv install` to create your virtual environment and install dependencies.
- Run `pipenv shell` to activate the virtual environment.

### Running Tests

- Run `pytest -x` to execute tests sequentially, stopping at the first failure.
- Tests are in the `lib/testing` directory.
- Tests check your regular expressions for names, phone numbers, and email addresses.
- The tests use the regex objects `name_regex`, `phone_regex`, and `email_regex` in `lib/regex.py`.
- Test cases cover valid and invalid input strings for each type.
- Use the detailed error messages from pytest to iteratively refine your regular expression patterns.

### Workflow

- Begin by writing a regex pattern to match the name `"John Cena"`.
- Run `pytest -x` and verify the first test passes.
- Continue refining your regex to pass all name tests.
- Repeat the process for `phone_regex` and `email_regex`.
- Once all tests pass, your lab is complete.

### Helpful Resources and Tips

- [regex101](https://regex101.com/) - an interactive site to build and test regular expressions.
- [Python `re` module documentation](https://docs.python.org/3/library/re.html) for detailed regex functionality in Python.
- Common regex shorthand:
  - `\w` matches any word character (letters, digits, underscore).
  - `\W` matches any non-word character.
  - `\s` matches any whitespace character.
  - `\S` matches any non-whitespace character.
- Use `|` to match alternatives.
- Escape special characters with a backslash (`\`).

***

## Key Vocabulary

- **Regular Expression**: A sequence of characters that specify a search pattern.
- **Pattern**: A description of sequences that the regex should match.

***

## Resources

- [re - Regular expression operations - Python](https://docs.python.org/3/library/re.html)
- [regex101](https://regex101.com/)
- [Python Regular Expressions - Google for Education](https://developers.google.com/edu/python/regular-expressions)

***

## Submitting Your Work

- Commit and push your changes in `lib/regex.py` to submit your lab.
