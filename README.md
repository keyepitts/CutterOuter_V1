This is my current router config using a RapidChange ATC tool changer in Gmoccapy/LinuxCNC 2.8. The tool change macro has been updated (1-22-24) to include disabling and re-enabling feed and spindle speed overides during the tool change process (thanks goes to Felix_P). I also added a few minor changes and more comments to the toolchange macro to make customization easier. The actual tool change macro is located in ncam/scripts/rack_change.ngc. This config has been running succesfully on my machine, but as always, use at your own risk.
