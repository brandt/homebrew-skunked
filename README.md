Homebrew-skunked
================
This repository is a [Homebrew](https://github.com/mxcl/homebrew) tap for formulae that didn't quite fit in.  In this case, mostly GUI and self-updating apps.

Think of it as an island of misfit toys, but instead of toys it's beer metaphors. And we don't mind if our beer is a little sour.

Tap it:
```
brew tap brandt/skunked
```

Then just install as usual with:
`brew install <formula>`

If a formula name conflicts, then use:
`brew install brandt/skunked/<formula>`

To untap it:
`brew untap brandt/skunked`


Also checkout adamv's [homebrew-alt][] which contains a wealth of unofficial formulae.


About Taps
----------
The Homebrew project is focused on maintaining the quality of their core formula list and are quite selective about the formulae they accept.

Sometimes that means a desirable formula gets left out.

That's where Taps come in. They allow you to extend Homebrew's formula list without the pain of merging forks.

Here are a few of the most notable taps:
 * [homebrew-alt][]
 * [homebrew-dupes][]
 * [homebrew-versions][]
 * [homebrew-boneyard][]


Depending on formulas in other taps
-----------------------------------
It's easy depend on formulas between taps.

Just include the tap path in the formula name.

For example:
```
depends_on "brandt/skunked/textmate"
```


Docs
----
`brew help`, `man brew`, or the Homebrew [wiki][].

[wiki]:http://wiki.github.com/mxcl/homebrew
[homebrew-alt]:https://github.com/adamv/homebrew-alt
[homebrew-dupes]:https://github.com/Homebrew/homebrew-dupes
[homebrew-versions]:https://github.com/Homebrew/homebrew-versions
[homebrew-boneyard]:https://github.com/Homebrew/homebrew-boneyard