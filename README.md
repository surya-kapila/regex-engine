# Motive
This is an ongoing series of build your own X , where I build and understand how various software programs/tools that we use everyday are designed and built.
# Build Your Own Regex
This is a test spec driven guide to help you build a simple regex engine.

This regex engine supports the following syntax:

| Syntax | Meaning | Example | matches |
|--------|---------|---------|---------|
| a | Matches the specified character literal | q | q |
| * | Matches 0 or more of the previous character | a* | "", a, aa, aaa  |
| ? | Matches 0 or 1 of the previous character | a? | "", a |
| . | Matches any character literal | . | a, b, c, d, e ... |
| ^ | Matches the start of a string | ^c | c, ca, caa, cbb ... |
| $ | Matches the end of a string | a$ | ba, baaa, qwerta ... |

The goal is to provide a syntax robust enough to match a large portion of regex use cases with minimal code. The included solution is under 40 LOC.

This repo has an accompanying blog post that explains the solution [here](https://nickdrane.com/build-your-own-regex/)

## Install

```js
npm install
npm test
```

## Requirements

This project requires a strong understanding of __recursion__ and wonderfully showcases it's elegance with a non-trivial example.

## Thanks
 This was possible due to Nicholas Drane's [build your own regex](https://github.com/nadrane/build-your-own-regex)
# regex-engine
