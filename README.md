# Ward: PEP 8 Auto-Enforcement Officer
blame PEP 8 anarchists for the errors of their ways.

## Usage
```sh
Ward

Usage: ward (-h | [-fad] FILE ...)

Options:
    -h --help       Display this usage information.
    -f --fail-fast  Stop enforcing after first violation.
    -a --angry      Enforce violations angrily. say your mind.
    -d --dart       Fire a correctional dart at the violater via email.
```

Firing correctional darts requires a `SENDGRID_API_KEY` environment variable.

## Example
```sh
$ ward ward
In ward:
    Ollie Ford is responsible for line too long (80 > 79 characters).
    Ollie Ford is responsible for whitespace before ']'.
    Ollie Ford is responsible for whitespace before ']'.
    Ollie Ford is responsible for missing whitespace around operator.
    Ollie Ford is responsible for line break before binary operator.
    Ollie Ford is responsible for whitespace before ']'.
    Ollie Ford is responsible for trailing whitespace.
    Ollie Ford is responsible for expected 2 blank lines, found 1.
```
