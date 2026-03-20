## Task-4:CSS Dropdown menu

## Features implemented:
## Step-1: Nested menu structure
    ->Used <ul> and <li> to create dropdown submenu
    ->The main menu contains the profile with subitems

## Step-2: Desktop Dropdown:
    ->On desktop screens, the submenu appears when the user hovers over the Profile menu.
    ->Implemented using CSS :hover pseudo-class
    
## Step-3: Smooth transition effect
    ->Used opacity:0 and visibility:hidden to ensure that the subitems appers only when hovered
    ->The submenu fades in and out instead of appearing suddenly.

## Step-4: Mobile responsive fallback:
    ->Mobile devies do not support hover so I have used :focus pseudo-class
    ->When we tap on the Profile link, it receives focus, and the submenu becomes visible.
    ->Used CSS media queries to adjust the menu layout on smaller screens.

