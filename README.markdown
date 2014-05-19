Games, on Steam for Linux [![Build Status](https://travis-ci.org/SteamDatabase/SteamLinux.png?branch=gh-pages)](https://travis-ci.org/SteamDatabase/SteamLinux)
=========================
This is the source code for *Games, on Steam for Linux*

License
-------
The content are under public domain.

Contribution
------------
If you want to edit the list, make a fork on GitHub, make your changes and then make a pull request through GitHub. Desribe your changes and be thorough! Follow the format, cite the sources, etc.

When editing the `GAMES.json` file, remember to follow the format with **tabs as indentation**, and not spaces.
Keep in mind that the list should be sorted numerically.

There are 2 tags that should know about:
* `"Working": true` for games that launch and work fine on Linux.
* `"Beta": true` for games that have open beta that can be opted in via beta branch in game properties.

If you want to add a comment, there are 2 tags you can use:
* `"Comment": "This game has no 64-bit binaries."`
* `"CommentURL": "https://google.com/"` - not required if there is no source url.

**Examples**
```json
	"234650":
	{
		"Working": true
	},
```

```json
	"15400":
	{
		"Working": true,
		"Comment": "May require a workaround to launch without getting stuck in a loop.",
		"CommentURL": "https://wiki.archlinux.org/index.php/Steam/Game-specific_troubleshooting#Harvest:_Massive_Encounter"
	},
```
Also make sure that the edited file validates on [JSONlint.com](http://jsonlint.com/) before submitting your patch.


Credits
-------
- [flibitijibibo](https://github.com/flibitijibibo) - Creator of The Big List of Steam Games on GNU/Linux.
- [swordfischer](https://github.com/swordfischer) - Re-made the list from scratch to use markdown and jekyll, then json.
- [xPaw](https://github.com/xPaw) - Improved the new list by making different stylesheet additions, and other minor improvements.
- [soeb](https://github.com/soeb) - Frequent contributor to the list.
- [weltall](https://github.com/weltall) - Frequent contributor to the list.
- [hypercephalickitten](https://github.com/hypercephalickitten) - Frequent contributor to the list.
- And a whole lot of very helpful people! Too many to list, truthfully.

Contact
-------
Most of us can be contacted on either #SteamLUG or #SteamDB on [Freenode](irc.freenode.net)
