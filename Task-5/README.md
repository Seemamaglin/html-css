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

