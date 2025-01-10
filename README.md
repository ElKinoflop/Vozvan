# Vozvan - Work In Progress - Case files not added yet
Stacked acrylic, handwired, monobody split, 12.75u, 40% keyboard

<img src="https://github.com/ElKinoflop/Barghest/blob/main/images/placeholder.jpg" alt="Vozvan Keyboard Photo">

Stacked acrylic keyboard case designed for handwiring with a <a href="https://mechboards.co.uk/products/pro-micro-5v?_pos=2&_sid=c64ff0323&_ss=r" target="_blank">Pro Micro footprint RP2040 controller</a>. 12.75u layout monobody split. Inspired by Peej's <a href="https://github.com/peej/lumberjack-keyboard" target="_blank">Lumberjack</a>, SquashKB's <a href="https://www.instagram.com/squash_kb/?hl=en-gb">Lesovoz</a>  and Trashman's <a href="https://trashman.wiki/keyboards/v4n4g0n">V4N4G0N</a>. The idea was to use all off the shelf components (other than the case). There are lots of options on what you could do with the central section. I just tried to arrange the wires in a neat way on the top part and added an encoder to the bottom part. Other ideas for the bottom section would be to add additional switches, push buttons, LEDs or an OLED display.

Feel free to do whatever you want with the files. If you have any questions just ask (Discord username elkinoflop) and if you make one then share a photo with me!

<h1>Layout</h1>
There are two versions of the layout. A stabless version and a version which requires 2x plate mounted 2u stabs. They both have the same amount of keys so your choice of layout doesn't change the matrix.

<h2>Stabless</h2>
<img src="https://github.com/ElKinoflop/Vozvan/blob/main/images/Vozvan%20Handwire%20KLE.jpg" alt="Vozvan Stabless KLE Image">

<h2>Stabbed</h2>
<img src="https://github.com/ElKinoflop/Vozvan/blob/main/images/Vozvan%20Stabbed%20KLE.jpg" alt="Vozvan Stabbed KLE Image">

<h1>KLE Raw Data</h1>
<h2>Stabless</h2>
["Esc","Q","W","E","R","T",{x:3.75},"Y","U","I","O","P",{w:1.75},"Back<br>Space"],
[{w:1.25},"Tab","A","S","D","F","G",{x:3.75},"H","J","K","L","@\n'",{w:1.5},"Enter"],
[{w:1.75},"Shift","Z","X","C","V","B",{x:3.75},"N","M","<\n.",">\n.",{a:7},"",{a:4},"Shift"],
[{w:1.25},"Hyper","Super",{w:1.25},"Meta","Hyper",{a:7,w:1.75},"",{x:3.75,w:1.75},"",{a:4,w:1.25},"Super",{a:7,w:1.25},"","",{w:1.25},""]

<h2>Stabbed</h2>
["Esc","Q","W","E","R","T",{x:3.75},"Y","U","I","O","P",{w:1.75},"Back<br>Space"],
[{w:1.25},"Tab","A","S","D","F","G",{x:3.75},"H","J","K","L","@\n'",{w:1.5},"Enter"],
[{w:1.75},"Shift","Z","X","C","V","B",{x:3.75},"N","M","<\n.",">\n.",{a:7},"",{a:4},"Shift"],
["Hyper","Super","Meta",{w:1.25},"Hyper",{a:7,w:2},"",{x:3.75,w:2.25},"",{a:4,w:1.25},"Super",{a:7},"","",""]

<h1>Case variants</h1>
<li>There are different variations of the case. Layers 1-7 are common across all variants but 0 (component cover), 8 (bottom) and 9 (feet) will change depending on which you choose</li>
<h3>Standard - ElectroCookie</h3>
Straight board with mounting points for an ElectroCookie protoboard. The specific case files for this variant will have SEC after the layer number
<h3>Standard - FeatherWing</h3>
Straight board with mounting points for an Adafruit FeatherWing. The specific case files for this variant will have SFW after the layer number
<h3>5 Degree V - ElectroCookie</h3>
5 Degree V board with mounting points for an ElectroCookie protoboard. The specific case files for this variant will have VEC after the layer number
<h3>5 Degree V - FeatherWing</h3>
5 Degree V board with mounting points for an Adafruit FeatherWing. The specific case files for this variant will have VFW after the layer number

<h1>Case Manufacturing</h1>
<ul>
  <li>Designed to be cut from 3mm acrylic</li>
  <li>Note that acrylic sheets can vary in thickness even if they are listed as 3mm. I have found that Perspex® typically measures at 3-3.1mm whereas Xintao (which most Chinese suppliers seem to use) typically comes in at 2.6-2.7mm. This doesn't matter too much except for your switches will be much more visible with thinner sheets.</li>
  <li>There is also the option to replace the bottom, feet and central component cover with angled 'V' versions. The other layers of the case remain the same. This is currently untested.</li>
  <li>As a rough idea of cost <a href="https://mechboards.co.uk/" target="_blank">Mechboards.co.uk</a> was the best price I could find in the UK at around £80-£90 (inc VAT) for the case and plate. This will vary depending on what acrylic you choose</li>
</ul>

<img src="https://github.com/ElKinoflop/Vozvan/blob/main/images/Vozvan%20Combined.png" alt="Vozvan Case Layers">

<img src="https://github.com/ElKinoflop/Vozvan/blob/main/images/Vozvan%20V%20Combined.png" alt="Vozvan V Case Layers">

<img src="https://github.com/ElKinoflop/Vozvan/blob/main/images/9d9e7bed-2c7b-4b43-9d6c-c64e370a0fa1.PNG" alt="Vozvan Case Render">

<img src="https://github.com/ElKinoflop/Vozvan/blob/main/images/Vozvan%20Orbit%20Explode.gif" alt="Vozvan Orbit Explosion">

<h1>Bill of Materials</h1>
<ul>
  <li>One of each case layer cut from 3mm acrylic. You need one of each number but you don't need for example both 8SEC and 8VEC.</li>
  <li>Either the stabless or stabbed plate DXF file cut from 1.5mm metal/carbon. Flexier/plastic plates aren't recommened as without a PCB you can bottom out the switches on the case and risk the switches popping out of the plate</li>
  <li><a href="https://mechboards.co.uk/products/pro-micro-5v?_pos=2&_sid=c64ff0323&_ss=r" target="_blank">Pro Micro footprint RP2040 controller</a></li>
  <li>M2 Standoffs with a outside diameter of 3mm. 4x 5-6mm for the feet, 10x 12-14mm for the main case, 6x 2-6mm for the proto board mounts. <a href="https://amzn.eu/d/8H1HG6Y" target="_blank">Amazon Standoffs</a></li></li>
  <li>M2 Hex socket button head bolts. Various lengths between 4-12mm. <a href="https://www.aliexpress.com/item/32969042589.html" target="_blank">AliExpress bolts</a></li>
  <li><a href="https://www.amazon.co.uk/dp/B08151V9TS?ref=ppx_yo2ov_dt_b_fed_asin_title" target="_blank">ElectroCookie PCB Prototype Board 3.8"x3.5"</a> OR <a href="https://www.adafruit.com/product/2884" target="_blank">FeatherWing Proto board</a>. Make sure you orient the board correctly before soldering. The ElectroCookie boards aren't symmetrical once you've broken them into 1x2 pieces, one side will be closer to the mounting holes than the other.</li>
  <li>Adhesive gasket material. 4mm width. I used 2mm thickn gaskets but ideally slightly thinner would be better.</li>
  <li>Wire! Solid core 22 AWG suggested</li>
  <li>46x MX Switches</li>
  <li>46x 1N4148 Diodes (plus any extras if you have buttons/encoders in the middle)</li>
  <li>Adhesive feet. If you are using the angle V version you may need thicker feet on the outer edges of the back feet as they are further rearwards</li>
  <li>Optional - 2x 2u Plate Mount Stabilisers if you are making the stabbed layout</li>
  <li>Optional - WS2812B LEDs. There's enough pins on the controller to add some RGB if you want. I used two of the <a href="https://www.aliexpress.com/item/1005007273486672.html" target="_blank">5x5 version of these</a>. Placing them under the prototype board gives a nice effect.</li>
  <li>Optional - Rotary Encoder (EC11). There's enough pins on the controller to add and encoder if you want</li>
  <li>Optional - 12*12*7.3mm tactile push button(s). These fit into the breadboard if you want some extra button(s) in the middle</li>
  <li>Optional - <a href="https://www.amazon.co.uk/dp/B08RMQP6YP?ref=ppx_yo2ov_dt_b_fed_asin_title" target="_blank">1.25mm Molex PicoBlade connectors and wire</a>. I used these to connect the matrix to the central section so they can easily be disconnected if required</li>
</ul>

<h1>Firmware</h1>
I used <a href="https://github.com/JanLunge/pog" target="_blank">POG</a>  to create <a href="https://github.com/KMKfw/kmk_firmware" target="_blank">KMK</a> firmware. POG makes creating firmware super simple but I might create QMK/VIAL firmware at some point!
I have included my firmware files (generated by POG). 

If you have wired up the matrix and connected it to the same controller pins as I have then you should be able to use my firmware. Install <a href="https://circuitpython.org/board/waveshare_rp2040_tiny/" target="_blank">Circuit Python</a> onto the controller first and then copy all the unzipped files from <a href="placeholder" target="_blank">'firmware PLACEHOLDER'</a> onto the drive.

<h1>Handwired Matrix</h1>
This is how I handwired the Matrix.
<img src="https://github.com/ElKinoflop/Vozvan/blob/main/images/Vozvan%20Matrix%20Pins.png" alt="Vozvan Handiwired Matrix">

<h1>Case Assembly</h1>
If you find some of the standoffs tight to push through don't force them. Use a small round file if you need to slightly widen any holes. The small round file from Draper 'Soft Grip Needle File Set, 140mm (6 Piece) (83982)' is the perfect size.

<img src="https://github.com/ElKinoflop/Barghest/blob/main/images/placeholder.jpg" alt="Vozvan Keyboard Photo">
