# afl-torrc-dict

A dictionary for `.torrc` files for use with [American Fuzzy
Lop](http://lcamtuf.coredump.cx/afl/), a security fuzzer. Generate
horrible `.torrc` files and see if you can get tor to eat them.

I have not yet found a crash in parsing using `afl-fuzz` and this
dictionary, with an instrumented version of `tor`.


### License

GNU GPL v3.


### Donate

No donations required. If you find a vulnerability in torrc parsing
with these dictionaries, please do the responsible thing and [tell the
Tor Project](https://www.torproject.org/about/contact.html.en#security)
about it.
