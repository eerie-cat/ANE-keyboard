ANE-keyboard for Mac OS X 
=======
File made with [Ukelele](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele) the Mac OS X Keyboard Layout Editor. 


Ancient Near Eastern Studies keyboard layout is a layout that lends itself to writing for Ancient Near Eastern Studies, namely there are Unicode character mappings for commonly used characters, e.g. āēīōū âêîôû ṣṭṯḫḡ and others.  

The keyboard is based on the U.S. Extended layout

## Installation

1. Download the project
1. Extract the `.keylayout` and `.icns` files and put in either your `/Library/Keyboard Layouts/` or `User/yourusername/Library/Keyboard Layouts/` directory. You might need to make the `Keyboard Layout` directory if one doesn't exist. 
1. Go to System Preferances > Keyboard and add the new keyboard.

## How to see the characters available? 
### Option and Option Shift
#### Direct input

![](https://cloud.githubusercontent.com/assets/536441/4001026/a3528b6a-295f-11e4-823c-96a7889f42be.jpg)

1. Turn on **Show Keyboard Viewer** 
2. Now press `Option` and notice the characters that have changed, e.g. 
  * `Option-1` = ă
  * `Option-2` = ŏ
  * `Option-3` = ĕ
3. Do the same now with 'Option-Shift' and you'll see not only some characters capitalize, but also, e.g. on the number row, characters like 'Option-Shift-4` = ᵉ, or 'Option-Shift-5' = ə. 

##### Special note
`Option-\` is a forced overbar over characters that do not have such a combination within Unicode. To use, type the character *first* then this deadkey, so it's backwards, as it were, e.g. `p` then `Option-\` will give `p̄`. 

#### Deadkey State: Option-Deadkey = 
1. With the Keyboard Viewer on, if you press `Option` you'll see colored keys. In this *deadkey state*, select, say, the `x` key, which appears as `.` on the Keybaord Viewer. Pressing the `x` key will then show all of the characters that have a  `.` underneath them, e.g. `ḥ` or `ṭ`. 



### Known Issues
1. `Option-.` and similarly `Option-Shift-.` = `null` This maps to Egyptological ayin ![Egyptological ayin](http://upload.wikimedia.org/wikipedia/commons/3/3d/U-A725_LATIN_SMALL_LETTER_EGYPTOLOGICAL_AIN.gif), but you'll need a font, e.g. [Aegyptus](http://users.teilar.gr/~g1951d/) that has this character included in the font table. 
2. `Option-/` and similarly `Option-Shift-/` = `null` This maps to Egyptological alef ![Egyptological alef](http://upload.wikimedia.org/wikipedia/commons/a/a6/U-A723_LATIN_SMALL_LETTER_EGYPTOLOGICAL_ALEF.gif)
2. 'Option-\` is a forced bar over
3. 'Option-Shift-0` = `null`  

### Troublshooting
If you're having issues, try going to `/Library/Keyboard Layouts/` or `User/yourusername/Library/Keyboard Layouts/` and removing the keyboard and then readding. It might not hurt to log out and in or at least relaunch Finder. 

If you have issues, add an issue and I'll take a look. 
