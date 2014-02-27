You can use it online: http://kafene.github.com/bookmarklet-combiner/bookmarklet-combiner.html

## UPDATE 2014-02-27

I've finally pushed my "version 2" today, the code is a lot leaner, runs much faster, and hopefully is less buggy. I removed most of the configurability, it's probably easier for both of us to just edit the CSS for the generated bookmarklet directly and run it off localhost... There is a new format for bookmarklet serialization its just pure json for bookmarklets and nothing else.

Removed configuration:

- Menu position: it's still there in the CSS, as `top:10px;left:10px;`. I wager this is acceptable to most people as default.
- Setting title: Just drag the link to your bar and rename it, easier than storing the title option along with the bookmarklets themselves.
- "Open all" behavior on click: I found this somewhat useless, and outside the scope of what I want to make, which is a menu for bookmarklets, not a runner that could be just as easily achieved by concatenating them.

**Features:**

* Use your browsers localStorage to save bookmarklets.
* Keep a JSON backup of the saved bookmarklets which can be restored later.
* Entirely self-contained, works offline, from your local computer.
* Checked with JSHint.
* Works in Opera!

*There are probably still some bugs* - I wrote this a long time ago to use personally. I haven't noticed any severe bugs, but I did some code cleanup before putting it onto GitHub. Hopefully everything works fine but if not then please submit an issue.

Originally based on, and inspired by: [Bookmarklet Combiner (w-shadow.com)](http://w-shadow.com/bookmarklet-combiner)
