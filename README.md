# km-fix-safari-cmd-1-9
*Summary:* Apple has changed the way that ⌘+1 through ⌘+9 work in Safari. This changes it back.

For as long as I can remember, Safari has used ⌘+1 through ⌘+9 to invoke the first 9 bookmarks in the “Favorites” toolbar.

In Safari in the public betas of 10.11 (“¡El Capitan!”), ⌘1 through ⌘9 are now used to select the first-through-ninth currently “open" tab, and if you want to invoke the favorites you have to use ⌥⌘1 through ⌥⌘9.

Well. No. I believe this “new way” is similar to other browsers, such as Google Chrome, and I am sure there are plenty of people who will prefer it, but I do not.

I mean, I like the idea of being able to jump to a specific tab, I guess, but I don’t like the idea of changing an entire muscle memory set to use a new feature, and having to develop a new muscle memory set to use the old feature that went with the old muscle memory set.

I kept thinking to myself, “Why didn’t Apple just make the *new* feature use the ⌥ key?”

So I made a set of [Keyboard Maestro][] macros which “fixes” this.

Now:

* ⌘1 will go to the first “Favorite” and ⌥⌘1 will select the first tab.
* ⌘2 will go to the second “Favorite” and ⌥⌘2 will select the second tab.
* and so on, for the rest of ⌘3 through ⌘9.

## To Install

[Download the Keyboard Maestro macro set][1], unzip, and double-click the .kmmacros file.

The macros will be added to Keyboard Maestro, into a group called “Only in Safari” which will, as you might have guessed, mean that those macros will only be used in Safari.

[Keyboard Maestro]:	http://www.keyboardmaestro.com/main/
[1]:	https://github.com/tjluoma/km-fix-safari-cmd-1-9/archive/master.zip

