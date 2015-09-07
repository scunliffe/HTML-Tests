# HTML-Tests
A collection of HTML tests.

As much as there are standards for how HTML should be parsed and rendered, anyone that has done web development knows that these "standards" are not gaurenteed and more importantly if you accidentally serve up *munged* content what the browser decides to render is not always known.

The included tests of both valid and invalid markup hope to provide the ability to test scenarios across different browsers under varying conditions.  e.g. all tests will include the standard HTML5 doctype `<!doctype html>` however if it is removed (or something gets output before it) the rendering will likely revert to quirks mode and may change the behavior.
