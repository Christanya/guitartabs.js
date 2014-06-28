## guitartabs.js

For a friends project I want to show off, what browser technologies can do, so I hacked this little browser based editor for guitartab songbooks.

### Features

* Enter songs in normal text, use Markdown to style the content.
* Add Tabs in square brackets inline
* Use the preview button in the editor to get a HTML rendered tab sheet
* Let it make a slide for you, with or without tabs, as you wish
* Select slide theme
* Select song fonts (that will be used on slide)

### Issues
* Marked is not made to be extended. Since I hate keeping a separate branch for a minor function, the detection of the chords does not happen in marked, but in a separate function. As soon as marked supports adding new syntax, this should be moved.
* The foont chooser widget sometimes underlaps the slide container. Clicking anything that the slide container overlaps does not work.
