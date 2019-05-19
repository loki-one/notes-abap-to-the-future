#ABAP in Eclipse

## Searching for artifacts in the abap repository using Eclipse
* Shortcut: `CTRL + Shift + A`.
* You can also add something like `Type:Interface` or similar after typing the first letters of the object.

## Bookmarking
* Right click on the artifact (that needs to be bookmarked).
* This opens the context menu.
* Click `Add Bookmark`.
* This adds to the bookmark section/box which can be seen on the right of the screen or on the bottom depending on how you have aligned your views in eclipse.

## Quick Assist (CTRL + 1)
* To create method definition from method call: `cursor on method call` + `CTRL + 1` + select respective option from the list.
* To create method implementation: `cursor on method` + `CTRL + 1` + select respective option from the list.
* To generate getters or setters for a variable: `cursor on the variable` + `CTRL + 1` + select respective option from the list.
* Moving methods and attributes (eg: move method from public to private): `cursor on method or attributes` + `CTRL + 1` + select respective option from the list.
* Generate instance constructor or class constructor: `cursor on the class name` + `CTRL + 1` + select respective option from the list.
* Generate surrounding Try-Catch block: `cursor on the method call that throws exception` + `CTRL + 1` + select respective option from the list.
* Add ABAP Doc for method/class: `cursor on the method/class definition` + `CTRL + 1` + select respective option from the list or menu path `Source code -> Import ABAP Doc from Descriptions`.

##  Method Extraction
* Shortcut: Highlight the code that needs to be extracted into its own method + `ALT + SHIFT + M`.
* Context Menu: Highlight the code that needs to be extracted into its own method + `Source -> Extract method`.

## Deleting Unused Variables
* In ABAP workbench: Transaction `SLIN`.
* In Eclipse: `Choose menu option Source -> Delete Unused Variables (All)`.

## Test Class creation
* Navigate to local class tab at the bottom and `type 'test'` and `CTRL + space`.
* Choose the option of test class creation.
* A generalized test class definition, implementation with demo method definition and implementation is created.
* To make the class name more specific to ours: `Put cursor on test class definition` and `CTRL + F1`. 
* The framework creates the whole class.

## Run Unit Tests and check coverage
* Run unit test: `CTRL + SHIFT + F10`.
* Run unit test with coverage: `CTRL + SHIFT + F11`.

## Pretty Print
* According to rules mentioned in preferences: `Shift + F1`.

## General features and shortcuts
* Changing font size: `CTRL + +` and `CTRL + -`. (Neon - 2016)
* Autosave: menu path `Windows -> Preferences + General + Editors + Autosave`. Then make respective autosave settings like how often. (Neon - 2016)
* Wordwrap: `ALT + SHIFT + Y`. (Neon - 2016)
* List of what is open, so that you choose an object to jump to: `CTRL + E`. (Oxygen - 2017)

