# minitest

A minimal test library for zepto. It is in early alphae

# Usage

The following endpoints are exposed:
```clojure
(assert-equal 1 1)
(assert-not-equal 1 0)
(assert-true #t)
(assert-false #f)
(assert-truthy [:non-empty-list])
(assert-falsy {})
(assert-nil (nil))
(assert-not-nil :any-val)
(all-passed) ; returns a boolean signifying whether all tests have passed
(exit-first-fail #t) ; if this is set to true, the program exits once a test fails
(results) ; prints test results
```

A minimal script named `zepto_tests` is also included.
Usage:
```bash
$ zepto zepto_tests test.zp # this will run the file test.zp and print results
```

<br/>

*Have fun!*
