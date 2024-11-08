MAX6818-debouncing-circuit
==========================
### UPDATES
- I did everything wrong. MAX6818 pulled up the buttons with internal pullup resistors.
  - [MAX6818-Based Debounced Breadboard Keypad | The Life of Kenneth](https://blog.thelifeofkenneth.com/2011/09/max6818-based-debounced-breadboard.html)

<img src="20240205_173454_HDR.jpg" width="300" height="auto">

### The [circuit](circuit-20240205-1915.circuitjs.txt) for [Circuit JS/Falstad](https://www.falstad.com/circuit/circuitjs.html)
<img src="circuit-20240205-1915.svg" width="500" height="auto">

### Output
<img src="20240205_173513_HDR.jpg" alt="image" width="300" height="auto"><br>
<img src="20240205_173526_HDR.jpg" alt="image" width="300" height="auto"><br>
<img src="20240205_173610_HDR.jpg" alt="image" width="300" height="auto">

### Notes
- Three-state Enable(Active Low, Pin 1) may be unneeded, if this is true, switches may omit the 5V supply (see [datasheet](max6816-max6818.pdf)'s page 1, untested)

### Related
- [dirkarnez/EIE3105_Debounce_Test](https://github.com/dirkarnez/EIE3105_Debounce_Test)
