# opk-wrap
take in a plain text value and "wrap" it in a JSON packet with the appropriate key

e.g.:

> echo 2.3 | ./wrap -s JSON -k temp

returns

> {"temp":2.3}

Note: you'll need to perform a 'chmod 7555 ./wrap' in order to be able to execute the wrap CLI as above'
