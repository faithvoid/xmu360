# xmu360
xmu360 - an Xbox 360 Memory Unit to Xbox Memory Unit adapter. (WIP)

## Required Components:
- Xbox 360 Memory Unit
- Original Xbox controller (or adapter / wireless receiver with memory card inputs)
- AMS1117 3.3V voltage regulator (as the memory card uses 3.3v as opposed to standard 5v that USB ports provide)
- USB-A female socket
- PCBs from your manufacturer of choice (not ready yet!)

## Installation:
- Populate the USB & 3.3v regulator slots on the PCB with the required components (if not pre-assembled)
- Insert the PCB into your Xbox controller or memory card adapter, then insert your Xbox 360 memory unit into the slot located at the top of the PCB.
- To verify that the adapter is working as intended, go to the Xbox dashboard, go to Memory, and your 360 memory card should show up as a standard Xbox memory unit!

## FAQ:
- "Why?"
Xbox Memory Units are unreasonably expensive (I paid $20 for an 8MB third-party controller), but people are virtually giving away their Xbox 360 memory units (you can find them as cheap as $5 on local listings), and seeing as they're official Microsoft products, feel like a great fit for the original Xbox.
- "Can I use this as both an Xbox 360 Memory Unit and an Xbox Memory Unit?"
Probably not. The original Xbox and the Xbox 360 both use FATX, but use different folder structures for their respective data which may cause issues between systems. In the case of issues, you can format the memory card on an Xbox or Xbox 360 as usual to properly partition it for that system.
- "Can I use the Skeleton Key payload with this adapter?"
Yes, as the Xbox 360 Memory Unit is, at it's core, just a USB adapter. I'd recommend using the USB version of the Skeleton Key payload, as you have 64+MB of space to work with. 
