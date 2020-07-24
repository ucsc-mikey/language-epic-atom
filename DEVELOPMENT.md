# How to Setup a Development Environment

This is just here to remind me how I setup Atom when I worked
on this project. It may be useful for others as well.

* Either create a new empty project from within Atom:
Packages -> Package Generator -> Generate Atom Syntax Theme

* Or check out a current one via github:
`bash$ git clone https://github.com/ucsc-mikey/language-epic-atom`

* Quit Atom (if it's running)

* In the terminal, `cd` to your project directory.

* Create a dev link using `apm`
`bash$ apm link --dev`

* Relaunch Atom in dev mode
`bash$ atom --dev .`

Changes to the grammars should be immediate, so open the PRS file
in one tab and the CSON file in the other.

Changes to the syntax highlighting require reloading:
View -> Developer -> Reload Window

To figure what scope your in, open the developer tools:
View -> Developer -> Toggle Developer Tools
Use the "select an element" icon (upper left) to click on the scope
you want to know about. This will let you examine the CSS classes
that are in that scope and allow you to modify as needed. Atom is
just HTML, after all. =)

## Helpful links:
* [Creating a Theme - Atom Manual](https://flight-manual.atom.io/hacking-atom/sections/creating-a-theme/)
* [Creating a TextMate Grammar - Atom Manual](https://flight-manual.atom.io/hacking-atom/sections/creating-a-legacy-textmate-grammar/)
* [Python Language Grammar, for reference](https://github.com/atom/language-python)
* [Boilerplate CSON file](https://gist.github.com/DamnedScholar/622926bcd222eb1ddc483d12103fd315)
* [TextMate Grammar Rules](https://macromates.com/manual/en/language_grammars)
