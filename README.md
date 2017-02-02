# browser
Utility for launching a Web browser.

This package was copied from the __Go__ repository: https://github.com/golang/go/tree/master/src/cmd/internal/browser

In the __Go__ distribution, `browser` is an internal package, so it cannot be imported from outside of the `cmd` package. Commands such as `go tool cover` use `browser.Open` to launch a Web browser and display HTML reports.
