ANE-keyboard for Mac OS X 
=======
File made with [Ukelele](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele) the Mac OS X Keyboard Layout Editor. 


Ancient Near Eastern Studies keyboard layout is a layout that lends itself to writing for Ancient Near Eastern Studies, namely there are Unicode character mappings for commonly used characters, e.g. āēīōū âêîôû ṣṭṯḫḡ and others.  

The keyboard is based on the U.S. Extended layout


## How to use the code
1. Paste the code into a text editor, e.g. [Atom](atom.io)
  * To rename the keyboard name, rename the value `name` in the line `<keyboard group="126" id="-2" name="ANE v3.5" maxout="3">`. This is the name that shows up in the keyboard menu. 
2. Save with the file extension `.keylayout`, e.g. `ANE.keylayout` in /Library/Keyboard layouts/ (could also be on User, but this is where I keep mine). You might need to make a directory if one doesn't exist. 
3. Now go to System Preferances > Keyboard and depending on your system (e.g. 10.9), there will be a way to add a new keyboard.
  * In 10.6, the full list of all keyboards were available and after enabling your new keyboard, you had to make sure an app you want to use the keyboard in launches anew in order for the app to *see* the new keyboard. Since I wanted to use the layout in more than one app, I'd usually just log out and in. In 10.9, this is no longer required :thumbsup:
4. If you want to have an icon for your keyboard, you'll need to add an `.icns` with the exact `name` as you gave it in 
 `<keyboard group="126" id="-2" name="ANE v3.5" maxout="3">` above

## How to see the characters available? 
### Option and Option Shift
#### Direct input

![option-deadkey](https://cloud.githubusercontent.com/assets/536441/4001026/a3528b6a-295f-11e4-823c-96a7889f42be.jpg)

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
