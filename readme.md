#heightFix.js

###Introduction
heightFix.js is designed to solve the problem of your background (or other section)
jumping on mobile when set with % height or vh, and the mobile browser hides the
address bar (Relevant stackoverflow [here]( http://stackoverflow.com/questions/24944925/background-image-jumps-when-address-bar-hides-ios-android-mobile-chrome)).

It solves the issue by setting the dynamic height (in % of the window, or vh) as a static height (in px) on load,
thus preventing a change when the screen resizes vertically. Additionally, heightFix detects changes to the window
width in order to resize sections if the screen is maximized (on desktop) or turned (on mobile.)

###Requirements
1. [jQuery](https://jquery.com/)
2. Some knowledge of how to use jQuery
3. heightFix.js

###Instructions
1. Make sure you've got [jQuery](https://jquery.com/) included in your html file.
2. Include heightFix.js on your page.
3. Set up your section heights within the init function.
