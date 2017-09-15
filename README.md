# module-basic-ui

### This repo contains the schematic and board layout for a simple, generic user interface consisting of a common 0.96" or 1.3" OLED monitor and three large buttons. Compact, cheap, and breadboard-ready. 

### We bought our buttons from Adafruit (https://www.adafruit.com/product/1010 or https://www.adafruit.com/product/1009) though there are lots of other footprint-compatible options in the Omron B3F button series (see https://octopart.com/search?q=omron%20b3f&start=0). Our OLED monitors currently come from Electrodragon (http://www.electrodragon.com/product/0-96-12864-oled-display-iicspi/), though we'd like to find a monitor of comparable price that is more widely distributed.

### PLEASE NOTE: different versions of the OLED monitors have the GND pin as either the first pin or the second pin. To accommodate, the module includes two footprints for the monitor. Soldering the monitor to the wrong footprint will ensure that the monitor burns out during normal use. Please carefully match your particular monitor to the right footprint -- the ground pins on each footprint are circled.
