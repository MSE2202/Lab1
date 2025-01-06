# IR Detector Assembly

An IR receiver module is used to receive signals that are transmitted over a particular carrier frequency. The MSE 2202 Lab Kit includes a TSOP32238 IR receiver that is tuned to 38 kHz. It is used by the MSEbot to detect and localize an IR beacon.

To faciliate integration with the MSEduino, a 3-wire connector is added to the TSOP. In addition, a 10 µF electrolytic capacitor is added to the power terminals to help reduce supply ripple.

## Instructions

The complete process of adding terminal connectors to the IR receiver is demonstrated in the following video.

[![IR Detector Assembly](https://img.youtube.com/vi/y7pB_BL9O_0/0.jpg)](https://youtu.be/y7pB_BL9O_0 "IR Detector Assembly")

1. **Begin by putting on a pair of safety glasses.**

2. Start with a 3-wire female–female connector and remove the connectors from one end. 

3. Strip about 3 mm of insulation from the wires and tin the ends.

4. Cut the legs of the TSOP32238 to a length of about 8 mm (5/16") and tin the ends of the leads.

5. Solder the wires to the TSOP32238.

6. Shorten the leads of a 10 µF electrolytic capacitor to a length of 7–8 mm and tin the ends.

7. Solder the capacitor to the TSOP32238. Ensure that the negative lead (marked by white band) is connected to the ground wire of the TSOP and the positive lead is connected to Vs.

8. **Be sure to wash your hands after handling solder.**

## Testing

The IR detector can be tested using the [IR beacon](IR-beacon-assembly.md) and the test code that is hosted in a separate repository on GitHub. It may be found at [https://github.com/MSE2202/BeaconTest](https://github.com/MSE2202/BeaconTest). You can download (or clone) the entire repository or only the sketch in the BeaconTest folder.

With the TSOP output connected to GPIO09, a serial monitor configured to 9600 baud can be used to display any received data (characters).

Alternatively, the signal from the output pin can be connected to an oscilloscope for observation, as shown in the figure below. The output from the TSOP is shown in yellow (CH1) and the signal from the beacon is shown in blue (CH2).

![IR Signals](figs/IR_signals.jpg)

## Resources

- [TSOP32238 IR Receiver Data Sheet](https://www.vishay.com/docs/82489/tsop322.pdf)