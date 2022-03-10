# KirbyCthulhu.github.io
Repo / Tools Library

**greenscreentransition.html**
Use this to create scenes in your desired streaming tool (OBS, Streamlabs, etc.) to enable displaying and hiding entire nested scenes.  
Useful for ads, alerts, socials, reminders, etc. that you only want to display for a short duration before hiding.
You can effectively turn any source into a hideable display.

Takes two query strings:
showChromaKeyInSeconds: Number of seconds to display green screen.  Use -1 for permanent greenscreen display.
hideChromeKeyInSeconds: Number of seconds to hide green screen.  Currently no permanent "white screen" as it didn't seem useful, but you could always set it stupidly high.

Example:
https://kirbycthulhu.github.io/greenscreentransition.html?showChromaKeyInSeconds=10&hideChromaKeyInSeconds=30

This would show the green screen for 10 seconds and hide it for 30.
