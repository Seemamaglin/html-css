## Task: CSS-Only Multi-Section Website (No JavaScript)

## Features Implemented:

## Step-1: Semantic page structure
    -> Used semantic HTML elements such as <nav> and <section>
    -> Each “page” is represented by a separate <section> element
    -> Sections include:
        => Home
        => Gallery
        => Menu
        => Visit Us

## Step-2: Navigation using anchor links
    -> Implemented navigation using <a href="#section-id">
    -> Each navigation link points to a corresponding section
    -> Enables page-like navigation without JavaScript

## Step-3: Page visibility control using :target
    -> All sections are hidden by default using:
        display: none
    -> The :target pseudo-class is used to display the active section
    -> Only one section is visible at a time, simulating page navigation

## Step-4: Smooth page transition animations
    -> Applied transitions using:
        opacity
        transform (translateY)
    -> Creates a smooth page-switching experience

## Step-5: Layout management using Flexbox
    -> Flexbox is used to:
        => Center content on the Home page
        => Align navigation links
        => Structure Visit Us content
    -> Ensures clean alignment across screen sizes

## Step-6: Layout management using CSS Grid
    -> CSS Grid is used for:
        => Gallery image layout
        => Menu category layout
    -> Grid automatically adapts to screen size using auto-fit and minmax

## Step-7: Responsive design using media queries
    -> Media queries adjust layout for smaller screens
    -> Navigation switches to a vertical layout on mobile
    -> Menu section becomes scrollable only on small screens
    -> Prevents unnecessary scrolling on large screens

## Step-8: Accessible navigation menu
    -> Navigation uses semantic <nav> and <a> elements
    -> Clear hover states for better usability
    -> Responsive layout ensures usability across devices

## Step-9: Visual overlay using pseudo-elements
    -> Used ::before pseudo-element on Home section
    -> Adds a semi-transparent overlay over the background image
    -> Improves text readability without altering the image

## Step-10: Visit Us section styling
    -> Styled using Flexbox 
    -> Adapts layout for smaller screens

## Step-11: State management
    -> Used :target pseudo-class for page state
    -> Used :hover and transitions for interactivity
