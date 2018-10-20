---
title: Check for All or None
---
## Check for All or None

This is a stub. <a href='https://github.com/freecodecamp/guides/tree/master/src/pages/certifications/javascript-algorithms-and-data-structures/regular-expressions/check-for-all-or-none/index.md' target='_blank' rel='nofollow'>Help our community expand it</a>.

<a href='https://github.com/freecodecamp/guides/blob/master/README.md' target='_blank' rel='nofollow'>This quick style guide will help ensure your pull request gets accepted</a>.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->


In General:
The RegExp constructor creates a __regular expression object__ for __matching text__ with a pattern. You can specify the pattern with rules. One rule is "?".

The __?__ in a RegExp is a __Quantifier__. 

In the Regexp "x?" matches the preceding item x 0 or 1 time.

For example:
*/e?le?/* matches the *"el"* in *"angel"* and the *"le"* in *"angle."*


If used immediately after any of the quantifiers *, +, ?, or {}, makes the quantifier non-greedy (matching the minimum number of times), as opposed to the default, which is greedy (matching the maximum number of times).


Side Note: RegExp is just great and used often in real-world scenarios. 



### Solution: 

```javascript
let favWord = "favorite";
let favRegex = /favou?rite/; // Change this line
let result = favRegex.test(favWord);
```
