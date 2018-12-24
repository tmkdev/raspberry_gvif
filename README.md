# raspberry_gvif
Project to mate a Sony CXB1457R to a Raspberry Pi DPI interface with the hope of driving a GVIF in car display

DPI - https://www.raspberrypi.org/documentation/hardware/raspberrypi/dpi/README.md 

CXB1457R - https://datasheetspdf.com/datasheet/CXB1457R.html 

Parts ordered. We wait now. 

----------
Digging around - found that the aftermarket interfaces run at 800x480. Sounds about right. Will try that first.

(From https://learn.adafruit.com/adafruit-dpi-display-kippah-ttl-tft/installation)
# Set screen size and any overscan required
overscan_left=0
overscan_right=0
overscan_top=0
overscan_bottom=0
framebuffer_width=800
framebuffer_height=480
 
# enable the DPI display
enable_dpi_lcd=1
display_default_lcd=1
 
# set up the size to 800x480
dpi_group=2
dpi_mode=87
 
# set up the hsync/vsync/clock polarity and format
dpi_output_format=454661
 
# set up the size to 800x480
hdmi_timings=800 0 40 48 88 480 0 13 3 32 0 0 0 60 0 32000000 6
