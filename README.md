Mocha Tap Reporter
======================

This reporter generates a TAP formatted report. It was forked from its original
author to ensure compatibility with Komodo IDE as well as to add suites to the
output.

Usage
-------
```
npm install mocha-ko-tap-reporter
mocha --reporter mocha-ko-tap-reporter
```

Example Output
-------------
```
$ mocha --reporter mocha-ko-tap-reporter
ok 1  should work
Mocha .............................................
ok 1 Mocha should not output colors to pipe
1..1
"grep" option .....................................
ok 1 Mocha "grep" option should add a RegExp to the mocha.options object
ok 2 Mocha "grep" option should convert string to a RegExp
1..2
"fgrep" option ....................................
ok 1 Mocha "fgrep" option should escape and convert string to a RegExp
1..1
# tests 4
# pass 4
# fail 0
# skip 0
```
