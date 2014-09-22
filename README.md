# CSS UNICODE RANGE

  Mobile-first classes for css-unicode-range.
  Set the desired css-unicode-range on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-unicode-range
```
View on [npm](https://www.npmjs.org/package/css-unicode-range)


## File Size

1.3K unicode-range.css
638B unicode-range.min.css

## The Code
```
.ur { unicode-range: U+26; }         /* single_codepoint */
.ur-1 { unicode-range: U+0025-00FF; }        /* codepoint_range */
.ur-2 { unicode-range: U+400; }              /* wildcard_range */
.ur-3 { unicode-range: U+0025-00FF, U+400; } /* multiple values can be separated by commas */

@media screen and (min-width: 48em) {
  .ur-ns {   unicode-range: U+26; }         /* single_codepoint */
  .ur-1-ns { unicode-range: U+0025-00FF; }        /* codepoint_range */
  .ur-2-ns { unicode-range: U+400; }              /* wildcard_range */
  .ur-3-ns { unicode-range: U+0025-00FF, U+400; } /* multiple values can be separated by commas */
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .ur-m {   unicode-range: U+26; }         /* single_codepoint */
  .ur-1-m { unicode-range: U+0025-00FF; }        /* codepoint_range */
  .ur-2-m { unicode-range: U+400; }              /* wildcard_range */
  .ur-3-m { unicode-range: U+0025-00FF, U+400; } /* multiple values can be separated by commas */
}

@media screen and (min-width: 64em)  {
  .ur-l {   unicode-range: U+26; }         /* single_codepoint */
  .ur-1-l { unicode-range: U+0025-00FF; }        /* codepoint_range */
  .ur-2-l { unicode-range: U+400; }              /* wildcard_range */
  .ur-3-l { unicode-range: U+0025-00FF, U+400; } /* multiple values can be separated by commas */
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

