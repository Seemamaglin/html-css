## Task-8: CSS Accordion Component

## Features implemented:

## Step-1: Accordion structure
    ->Used an unordered list (<ul>) to hold multiple accordion sections
    ->Each section is wrapped inside a <li> element
    ->Every section contains:
        =>A hidden checkbox input
        =>A label acting as the clickable header
        =>A content container for expandable text

## Step-2: Hidden checkbox for state control
    ->Used <input type="checkbox"> to manage open and close states
    ->Checkbox is hidden using display: none
    ->The checkbox state controls both content visibility and arrow rotation

## Step-3: Label-based interaction
    ->Used <label for="section-id"> as the clickable accordion header
    ->Clicking the label toggles the corresponding checkbox
    ->This enables interaction without using JavaScript

## Step-4: Content visibility using :checked
    ->Content is hidden initially using:
        max-height: 0
        overflow: hidden
    ->Used the :checked pseudo-class with the general sibling selector (~)
    ->When the checkbox is checked, the content expands

## Step-5: Smooth expand and collapse animation
    ->Applied CSS transitions on max-height
    ->This creates a smooth animation when content opens and closes

## Step-6: Arrow indicator for open/close state
    ->Added a right arrow icon using the ::after pseudo-element on labels
    ->Arrow rotates when the section is expanded

## Step-7: Multiple section support
    ->Each accordion section uses an independent checkbox
    ->Allows multiple sections to be opened simultaneously
    ->Can be restricted to a single open section by replacing checkboxes with radio buttons