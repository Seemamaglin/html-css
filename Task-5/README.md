Task-5: CSS Modal Popup (Using :target)
Features implemented:

Step-1: Popup trigger using anchor link
    -> Used an anchor tag with href="#popup" to trigger the popup
    -> Assigned a matching id="popup" to the popup container

Step-2: Popup container structure
    -> Created a popup overlay container and inner popup content
    -> Popup content is placed at the center of the screen

Step-3: Visibility control using :target
    -> Used opacity: 0 and visibility: hidden to hide the popup initially
    -> When the popup is targeted, :target makes it visible

Step-4: Smooth transition effect
    -> Added CSS transitions for a smooth fade-in and fade-out effect
    -> Popup appears and disappears without JavaScript



Task-5: Modal Popup using :checked (Checkbox Hack)
Features implemented:

## Step-1: Hidden checkbox 
    ->Used an <input type="checkbox"> to control the open and close state of the popup.
    ->The checkbox is hidden using display: none 

## Step-2: Label-based open and close actions
    ->Used <label for="popup-toggle"> as the Open Popup button.
    ->clicking the label toggles the checkbox state.

## Step-3: Popup visibility using :checked
    ->Used the :checked pseudo-class to detect when the checkbox is selected.
    ->Applied the general sibling selector (~) to show the popup when the checkbox is checked.
