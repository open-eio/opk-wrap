# opk-wrap
take in a plain text value and "wrap" it in a JSON packet with the appropriate key

e.g.:

> echo 2.3 | ./coating -s JSON -k temp

returns

> {"temp":2.3}
