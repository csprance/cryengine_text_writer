# Text Writer
> Create text in CRYENGINE using a designer object

## Installation
* Copy the text_writer folder to Editors/Scripts
* Copy the text_writer_shelf to Editor/Scripts/Shelves
* Create a new map
* Import the font_bebase_neau layer into your newly created level.

# How to use
* Run the script from the toolbar or the Python Scripts panel.
* Enter your text and hit Ok
* Once finished *YOU MUST* copy paste the created designer objects to a new layer so each designer object gets a new name. Do not modify anything on the font_bebas_neau layer
    * Select all the polygons of the designer object
    * Merge it down
    * Export as a cgf.
* Rinse and repeat.
    * If you get an error after creating the first text item reload the font_bebas_neau layer and everything will work fine again


## Allowed Characters
```
ABCDEFGHIJKLMNOPQRSTUVWXYZ
1234567890
!$,-./@?>
```