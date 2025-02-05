# Changelog

## v0.29

- Added sounds for clicking and hovering over buttons.
- Automatic update checking is now an option that can be toggled in
  map settings (gear icon) -> "kklee settings".
- Multiple colours can now be specified in gradients.
- Made a kklee guide that is available on the GitHub page.

## v0.28

- Improved verification of being the original map author in the transfer
  ownership feature
- Made selection buttons in shape multiselect simpler by adding a dropdown for
  specifying whether to include shapes from the current, all or multiselected
  platforms
- Added a button in shape multiselect that selects physics shapes

## v0.27

- Fixed colour picker and image overlay after being broken by bonk.io update
- Minor improvements
- Name property in multiselect will now evaluate arithmetic

## v0.26

- Prevented arrow keys from scrolling page while panning editor preview
- Added a button that splits a concave polygon into convex polygons

## v0.25

- Added arrow key shortcuts to pan the camera in the editor preview
- Removed the fullscreen button, use
  <https://greasyfork.org/en/scripts/436028-fullscreen-bonk-io> instead

## v0.24

- Some minor UI improvements
- Added more buttons for multiselecting shapes, such as selecting all shapes
  from all platforms
- Added capture zone settings to shape multiselect
- Changed the default capture zone type to Instant Red Win when pressing the
  "Capzone" button in shape properties

## v0.23

- Some minor UI improvements and bug fixes
- Pasting platforms in multiselect will paste them in the opposite order to
  to how they were pasted previously
- Added a way to multi-select shapes by colour
- Colour pickers in kklee will use Bonk's colour picker
- Added another copy & paste option to platform multi-select in which joints
  on pasted platforms will be attached to the original platforms

## v0.22

- Added a way to overlay an image over the editor preview
- Added an indicator on the preview speed slider to show where normal speed is

## v0.21

- Copying shapes in multi-select will also copy capzones
- Added copy & paste to platform multi-select (though joints aren't copied
  properly)
- Fixed a minor bug when making the chat box visible in editor

## v0.20

- Fixed bug in ellipse generator
- Made the existing colours container in the colour picker have a maximum height
  and a scroll bar
- Added 0 as a value to preview speed slider
- Fixed the chat box autofill bug
- Added up/down arrow shortcuts for changing number number field value with
  Ctrl, Shift and Ctrl+Shift modifiers

## v0.19

- Changed how map backups are stored
- Changed some UI styles
- Increased shape generator shapes/vertices limit from 99 to 999
- Added polygon scale property to shape multi-select
- Added a way to rotate and scale multi-selected shapes around a point

## v0.18

- Fixed a bug in the ellipse generator that caused the first vertex to be
  repeated
- Added a colour gradient option to shape multi-select
- Added automatic backups of maps to the browser's offline storage

## v0.17

- Fixed bugs in the Shift+Space shortcut
- Shift+Esc will be usable even if the game wasn't started from the editor
- Fixed the bug in the gradient generator that caused the final colour to be
  part of the transition instead of the actual colour you chose
- Added a button that reverses the selection order in multi-select
- Added a button that reverses the order of selected items in multi-select
- Added a map size info panel that shows the total number of shapes, platforms,
  etc
- Fixed a bug in the corner rounder

## v0.16

- Added a variable for the number of selected items in multi-select
- Added rand function to arithmetic evaluators
- Added a link to the list of supported functions in multi-select
- Added ability to multi-select by item name
- Added a button to make the game frame fill the entire page

## v0.15

- Fixed bug in shape capture zone adder
- No physics shapes won't be counted in total platform mass
- Added inner grapple and shrink properties to shape multi-select
- Added ability to move shapes and platforms up/down in multi-select
- Highlighted properties in multi-select will be purple and bold instead of red
- Shift+Click will automatically open multi-select if it isn't already open
- Added a button that converts rectangles to polygons

## v0.14

- Fixed the custom colour picker that was broken in the latest Bonk.io update
- The browser's default action for Shift+Esc will be prevented when you use it
  return to the editor
- Properties in multi-select will be highlighted in red if they are modified

## v0.13

- Added platform multi-select
- Added a button in multi-select to invert selection
- Added index labels to selected shapes
- Added a label for a platform's total mass

## v0.12

- Added ability to transfer map ownership to a contributor of a map if you are
  the original author
- Added ability to round the corners of a polygon in the vertex editor
- Added the shape name property to the shape multi-select editor

## v0.11

- Fixed bugs in the vertex editor
- Added a button in shape properties that adds a new or views an existing
  capture zone for that shape
- Negative numbers can now be used in vertex scaling
- Changed shortcut for returning to editor after pressing play to Shift+Esc

## v0.10

- Removed the "move to platform" feature in multi-select
- Removed multi-duplicate and added option to specify how many times copied
  shapes should be pasted
- Changed multi-select angle unit from radians to degrees
- Added buttons to select or deselect all shapes
- Added option to automatically multi-select generated shapes
- Fixed a bug in multi-select that caused kklee to crash
- Made Shift+Space also return you back to the editor

## v0.9

- After applying in multi-select, shape properties will be updated immediately
- Added shape multi-duplicate. This lets you duplicate a shape a specified
  number of times and the duplicates will be automatically multi-selected
- Added keyboard shortcuts: Save - Ctrl+S, Preview - Space, Play - Shift+Space
- Moving shapes to other platforms is now an option in multi-select
- Added ability to copy and paste shapes in multi-select

## v0.8

- Fixed bug in the shape generator that caused the editor to break

## v0.7

- Added shape colour option to multi-select
- Added rect height option to ellipse and sine wave generators
- Added parametric equation generator

## v0.6

- Improved description for the shape multi-selection panel
- Added a label for the preview speed slider
- Added a tip about arithmetic evaluation
- Added ability to delete selected shapes in multi-select

## v0.5

- Make polygon merger work with scaled polygons
- Fix bug where chat scrolls to the top when you enter the map editor
- Added multi-select for shapes

## v0.4

- Fix annoying bug where chat would scroll up when you click it

## v0.3

- Moved the chat box to a better place
- Fixed the bug where the chat box disappears if you get disconnected from
  the server while editing a map
- Added option for easing gradients

## v0.2

- Added automatic checking of updates (you'll still have to install them
  manually)
- Added generators for linear and radial gradients
- Fixed bug in checkboxes
- Added changelog.md

## v0.1

First release

Features:

- The chat is visible in the map editor
- Vertex editor
- (Buggy) Merge multiple polygons into one
- Easily generate ellipses, spirals and sine waves
- Move shapes to other platforms
- Ability to use your browser's colour picker for changing colours
- Evaluate arithmetic in number fields by pressing Shift+Enter
  (example: type `100*2+50` into X position field and press Shift+Enter)
- Change the speed of map testing in the editor
