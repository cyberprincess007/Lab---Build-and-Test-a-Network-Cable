# Lab---Build-and-Test-a-Network-Cable
In this lab, I built my own Ethernet cable using the T568B wiring standard. I measured and cut the cable, arranged the wires in the correct order, crimped on RJ‑45 connectors, and tested it with a cable tester. I then connected it to devices to confirm it worked by checking the link lights and running network tests like ping.

## Objective
Construct and test a straight-through Unshielded Twisted-Pair (UTP) Ethernet cable following TIA/EIA T568A or T568B wiring standards, then verify functionality using a cable tester and connected devices.

## Tools Used
- UTP Ethernet cable (Category 5 or 5e)
- RJ-45 connectors
- RJ-45 crimping tool
- Wire cutters and strippers
- Ethernet wire map tester
- Two computers with NICs installed
- (Optional) Ethernet cable meter or certification meter

## Summary of Tasks
1. **Obtain and Prepare the Cable**
   - Measured and cut a length of UTP cable appropriate for the connection (added ~12 inches for flexibility).
   - Removed ~2 inches of cable jacket from both ends.
   - Selected wiring standard: **T568A** or **T568B**.

2. **Arrange and Insert the Wires**
   - Untwisted and arranged pairs according to the chosen standard.
   - Flattened wires in correct order and trimmed to ~0.5–0.75 inches from the jacket.
   - Inserted wires into RJ-45 connector with key facing down.
   - Ensured all wires were pushed fully to the connector’s end.

3. **Crimp and Inspect**
   - Crimped connector using RJ-45 crimping tool.
   - Verified color alignment and that cable jacket was inside the connector for strain relief.
   - Repeated process for the second end of the cable.

4. **Test with a Cable Tester**
   - Connected both ends to cable tester.
   - Verified all pins sequenced correctly with green lights.
   - Noted any wiring faults and corrected if needed.

5. **(Optional) Test with Cable Meter**
   - Verified cable length and performance using a cable meter or certification meter.

6. **Test the Cable in a Live Network**
   - Connected two computers, or a computer to a switch/router, using the cable.
   - Verified link lights illuminated on NIC ports.
   - Used `ipconfig` to confirm IP address assignment.
   - Pinned default gateway to verify successful communication.

## Outcome
- Successfully built a functional straight-through Ethernet cable.
- Verified proper wiring order according to TIA/EIA standard.
- Confirmed physical connectivity with link lights and cable tester results.
- Demonstrated the ability to create custom Ethernet cables for networking use.

## Skills Demonstrated
- UTP cable preparation and termination
- Applying TIA/EIA T568A or T568B wiring standards
- Crimping RJ-45 connectors
- Cable continuity and pinout testing
- Basic network connectivity testing with `ping` and `ipconfig`
- Troubleshooting cable faults

## Notes
- Minimize wire untwisting to reduce crosstalk.
- Ensure cable jacket is inserted far enough into the connector for durability.
- Straight-through cables are typically used to connect end devices (PCs) to switches or wall jacks.
