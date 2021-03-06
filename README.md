# Character information

* Authors: Cyrille Bougot
* NVDA compatibility: 2017.3 to 2019.3
* Download [stable version][1]
* Download [development version][2]

This add-on allows to present in a message character information such as unicode name, number, category, etc.


## Commands

* Numpad2 (all keyboard layouts) or NVDA+. (laptop layout): when pressed 4 times, displays information about the character of the current navigator object where the review cursor is situated.


## Notes

* This add-on provides also a script to display directly the review cursor character information. This script has no default gesture assigned. If you feel unconfortable with the four press gesture, you may assign to it a gesture in NVDA's input gesture dialog ("Text review" category).
* The provided information is in english since it is part of Unicode norm. If a local translation exists for this add-on, the information is also provided alongside with english.
* The CLDR name (Unicode Common Locale Data Repository) is only supported with NVDA 2019.1 and above.
* For the characters written with Microsoft proprietary fonts Symbol, Wingding (1, 2,, 3) and Webding, some additional information is provided: character name, font name and information of the corresponding unicode character.


## Change log

### Version 1.3

* Fixes a bug with NVDA 2019.3.


### Version 1.2

* Provides additional information on characters written with Microsoft fonts.


### Version 1.1

* Updates to support newer versions of NVDA (Python 2 and 3 compatible)
* Releases performed now with appveyor


### Version 1.0

* Initial release.

[1]: https://addons.nvda-project.org/files/get.php?file=chari

[2]: https://addons.nvda-project.org/files/get.php?file=chari-dev
