## Down

Blazing fast Markdown rendering in Swift, built upon [cmark](https://github.com/jgm/cmark).

Forked from [iwasrobbed/Down](https://github.com/iwasrobbed/Down).

### Installation

Using [Carthage](https://github.com/Carthage/Carthage):

```
github "Dooer/Down"
```
Due to limitations in Carthage regarding platform specification, you need to define the platform with Carthage. 

e.g.

```carthage update --platform iOS```

Or manually install:

1. Clone this repository
2. Build the Down project
3. Add the resulting framework file to your project
4. ?
5. Profit

### Robust Performance

>[cmark](https://github.com/jgm/cmark) can render a Markdown version of War and Peace in the blink of an eye (127 milliseconds on a ten year old laptop, vs. 100-400 milliseconds for an eye blink). In our [benchmarks](https://github.com/jgm/cmark/blob/master/benchmarks.md), cmark is 10,000 times faster than the original Markdown.pl, and on par with the very fastest available Markdown processors.

> The library has been extensively fuzz-tested using [american fuzzy lop](http://lcamtuf.coredump.cx/afl). The test suite includes pathological cases that bring many other Markdown parsers to a crawl (for example, thousands-deep nested bracketed text or block quotes).

### Output Formats
* HTML

### Supports
Swift, ARC & iOS 8+

### Markdown Specification

Down is built upon the [CommonMark](http://commonmark.org) specification.

### Credit
This library is a wrapper around [cmark](https://github.com/jgm/cmark), which is built upon the [CommonMark](http://commonmark.org) Markdown specification. 

[cmark](https://github.com/jgm/cmark) is Copyright (c) 2014 - 2017, John MacFarlane. View [full license](https://github.com/jgm/cmark/blob/master/COPYING).
