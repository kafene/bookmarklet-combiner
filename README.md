You can use it online: http://kafene.github.com/BookmarkletCombiner

**Features:**

* Use your browsers localStorage to save bookmarklets
* Keep a JSON backup of the saved bookmarklets which can be restored later
* Entirely self-contained, works offline, from your local computer
* Possible to change bookmarklet menu style, position, etc, to suit your tastes
  * Note: doing this requires editing of the file. Currently no menu CSS is saved,
    but it is possible a future version will have this feature.
* Checked with JSHint.
* Works in Opera!

**Requirements:**

* A browser that supports `JSON.parse()` and `JSON.stringify()`

*There are probably still some bugs* - I wrote this a long time ago to use
personally. I haven't noticed any severe bugs, but I did some code cleanup
before putting it onto GitHub. Hopefully everything works fine but if not
then please submit an issue.

Originally based on, and inspired by: [Bookmarklet Combiner (w-shadow.com)](http://w-shadow.com/bookmarklet-combiner)
