# Alternative Prototype Board for Benchduino
 
www.hamradioworkbench.com has designed and sells a general purpose development
board for Microcontrollers. They have provided the designs for both the CPU
Daughterboards as wells as the addon Prototype board.

This repository contains an alternative Prototype board that I designed. It provides 
builtin I2C, SPI, USB Host, and additional encoder, and serial inputs. The center
hosts a small breadboard for specialized prototyping.

Subdirectories include:
- Gerbers - this directory includes a zip file that you should be able to upload to
            your favorite Fab house.
- PCBDesign - This design is only available in  KiCad. It is a 4 layer design. The zip
            file is a KiCad archive that you shoule be able to just expand
- Documentation - This directory contains a schematic (pdf format) and a partial BOM 
            in Digikey format. It is not complete (I did not itemize the pin headers)
            and some of the parts I actually purchased from Amazon so was not confident
            that I could select the correct Digikey part.

There is absolutely no warranty here. Use this at your own risk!

BTW: JCLPCB charges a $35 engineering fee for this board because it is 4 layer and
greater than 100mm x 100mm. Perhaps someone wants to rework it into a 2 layer board?

73
Mark Hatch
AJ6CU