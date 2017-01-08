# tixati-dark-theme
A simple tixati dark theme

I changed the default css to make it dark.
The color scheme for the transfers isn't perfect, but I've been using it for quite some time and I got used to it (you are free to change it if you want ofc).

Since I almost only use the tranfer and the bandwidth tab, the major changes are on those two:

Transfer tab:
  - Added a jquery function on page load that inverts the order of the lines in the tranfer tab, so that the downloading and seeding files are on top of the page instead.
  - The controls that used to be at the bottom are now in an hidden tab that can be shown clicking the "Controls" button on the top right of the visible control bar (clicking the "Controls" button another time hides the panel again)
  - The main control bar has 5 buttons and an input text box: the first three have been just repositioned (Start, Stop and Delete files) and are enabled only when at least a tranfer is selected. The input box is for the magnet links (pro tip: there's a enter key listener in this page; when the magnet links input is not empty, pressing the enter key is the same as pressing the "Add" button in the main control panel)
  - If you need to upload a .torrent file instead, the old way of adding torrents is still available: you need to go to Controls->Advanced Add
  - All the other buttons you see have the same action as in the default theme.
  - In the top right, instead of the Help tab, is shown the current download (D) and upload (U) speed as they would be shown in the bandwidth tab
  - The Help tab link is visible in the other sections (Home, DHT etc.)

Bandwidth tab:
  - Minor changes to show the current donwload and uplaod speed
  
That's pretty much it, I liked the default webui for its semplicity, so I kept it that way, tweaking just what I needed.


Thanks to the tixati devs for this awesome client :D
