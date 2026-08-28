
# Aerofox


Aerofox is a WIP Internet Explorer 7 and 8 userchrome CSS theme for Firefox 153 ESR, a spiritual successor of RinFox, a theme for Firefox 115 ESR, which I plan to migrate from, and aims to make it feel more native to IE7/8, add in new features and QOL improvements such as animations, and it plans to make the web work for you.

Aerofox is based mainly from Rinfox, an Internet Explorer 7/8 theme for Firefox 115 ESR, set to end support in March 2027 (until further notice), with the elements being adapted for the new UI id's and classes. It also contains parts from BeautyFox 1, an Internet Explorer 9 theme also for Firefox 115 ESR, and Geckium, which has a modern foundation, supports Firefox 153 ESR, and has the necessary JS logic, which i plan on understanding soon.


## NOTICE:


This theme is currently in its indev phase, and i'm still developing the theme. Expect lots of bugs in this phase.


## INSTALLATION


To be added

## CONTRIBUTION
Although I don't wanna add any contributors yet, you can contribute by adding issues and fixes in the "Issues" section, and the "Pull requests" section allows you to share your modified code for me to test out. Contribution is highly encouraged and will especially help with large goals, such as the Windows 10 or 11 native context menu.


## GOALS:

This list isn't ordered in any particular way.

1. Figure out how Geckium uses JS as an equivalent to "@supports moz-bool-pref("uservalue")", as that's required for the IE8 theme, theme options, and more.
2. (Help needed) Somehow get the windows 10 and 11 native context menus to work in FireFox 153 ESR, as the about:config toggle "browser.display.windows.non_native_menus" stopped working in FF128ESR and above. Otherwise, recreate as many .msstyles menu textures as possible if there's no way to bring them back
3. Transform Geckium's settings page to look like an original IE7/8 inspired page, and understand and modify the JS code to update the about:config settings
4. Transform the first boot startup of geckium to look like a beautified version of Internet Explorer 7's initial setup screen, with animations and quick, easy setup options
5. Return the Windows XP mode hidden in the original RinFox via an about.config toggle
6. Add a classic windows mode
7. Make everything look more like Internet Explorer 7, and soon, Internet Explorer 8
8. Make an easy installer .bat script to install the latest version of FF153ESR using winget, installing in a custom directory, making backups of every profile in case a future FF version messes up bookmarks and more, uses resource hacker command line to automatically replace the icons of firefox.exe and privatebrowsing.exe, and somehow injecting "toolkit.legacyUserProfileCustomizations.stylesheets" into prefs.js after i learn how.
9. (Help encouraged) Disable FF153ESR's auto update system and replace it with a custom userscript javascript installer with another custom IE7/8 inspired interface, with automatic resource hacker command line, so users don't have to manually replace the files again after updating
10. Redesign the Firefox settings interface with UserContent.css
11. Bring back Quick Tabs via an extension that's easier and doesn't open seperately in a new tab like Tip Tab (I know the name, but i will show the name later)
12. Borrow JS code from Beautyfox to restore the Page, Tools, and for IE8, Safety dropdown button on the command bar
#### More goals coming soon


## CREDITS

#### Developers
XperiencedTang06, creator, manager, and main developer of Aerofox

Travy_patty, creator of 07Fox, and it's successor for FF115 ESR, RinFox, the main theme Aerofox is based on

angelbruni, original creator and manager of BeautyFox, and current manager of Geckium

dominichayesferen, current manager of BeautyFox and contributor of Geckium

More to be added


#### Projects
Rinfox

Geckium

BeautyFox 1 
