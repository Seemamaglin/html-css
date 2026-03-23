Task-6: CSS Tabbed Content Interface
Features implemented:

Step-1: Tab structure using radio buttons
    ->Used hidden radio buttons to store the active tab state
    ->Each tab is linked to a label using the for attribute

Step-2: Tab buttons using labels
    ->Labels act as clickable tab buttons
    ->Only one tab can be active at a time because all radios share the same name

Step-3: Content visibility using :checked
    -> All tab contents are hidden by default using opacity and visibility
    ->When a radio button is checked, the corresponding content is displayed
    ->Implemented using the CSS :checked pseudo-class and (~)css combinators

Step-4: Active tab highlighting
    ->The currently selected tab is visually highlighted
    -> Styling is applied to the label linked to the checked radio input

Step-5: Smooth transitions
    -> Used CSS transitions on opacity to create a smooth fade effect
    ->Tab content switches smoothly without using JavaScript
