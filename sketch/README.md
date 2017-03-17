# Sketch

## Scale

Always design in @1x scale

## Layer naming convention

Group\_Component\_State\_Name
	
	ex:
	
	1. icon_button_normal_like
	2. tile_background_normal_profile

### Group

**General**

* icon - Icon should always be black as its default color
* image
* tile - A repeatable image

### Component

**General**

The components apply across all platforms

* button
* switcher
* slider
* background
* alert

**iOS**

The standard iOS components

* tabBar
* navigationBar
* textField
* textView
* segmentedControl

### State

The different states for a single component

* inactive
* normal
* highlighted - 
* selected - Something switches on
* empty - No content