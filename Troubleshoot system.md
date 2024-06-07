## Scenario

You work at a computer repair store. A customer brought in a computer and asked you to upgrade the motherboard. You replaced the motherboard with a newer model, but now the computer will not boot. In addition to the new motherboard, the computer currently contains the following:

- Intel i7-960 processor

- 12 GB of DDR3 memory

- Two SATA hard drives (one with the operating system installed, and the other with a single volume for storing data)

- A single SATA optical drive


### Steps to Resolve


1. **Attempt to Power On the Computer**
   - On the computer, select the power button.
   - Select OK to close the prompt indicating that the computer failed to run.
   - This is most likely due to the computer not getting power.

2. **Provide Power to the Computer**
   - Above the computer, select Back.
   - Select the AC Power Connector (Female) that is currently plugged into the power supply.
   - Notice that the other end is not connected.
   - From the Selected Component pane, drag the AC Power Connector (Male) to an open outlet on the wall plate.
   - Above the computer, select Front and then select the power button.

3. **Check if the Computer Powers On**
   - The computer still won't start.
   - Select OK to close the prompt.

4. **Connect the Case's Power Switch to the Motherboard Header**
   - Above the computer, select Motherboard.
   - Notice that under Partial Connections for the computer, the system case is shown.
   - Under Partial Connections for the computer, select the system case.
   - From the Selected Component pane, drag the Connector, Case, Power Switch to the motherboard header (bottom right).
   - If needed, view the motherboard details to find the connection areas.
   - Above the computer, select Front and then select the power button.

5. **Check if the Computer Boots**
   - The computer boots to Windows, but soon powers off. This is typically caused by the computer overheating.
   - Select OK to close the prompt.

6. **Provide Power to the Heat Sink and Fan**
   - Above the computer, select Motherboard.
   - Notice that, under Partial Connections for the computer, the heat sink and fan is shown.
   - Under Partial Connections for the computer, select the heat sink and fan.
   - From the Selected Component pane, drag the Connector, Fan, CPU 4-pin that is connected to the motherboard (top center).
   - Above the computer, select Front.
   - On the computer, select the power button.
   - The computer powers on and stays on.

7. **Verify Hardware Recognition**
   - Verify that the memory (12 GB), two hard drives, and an optical drive are recognized.
   - Right-click Start.
   - Select Shut down or sign out > Restart.
   - When you see the TestOut splash screen, press F2 (or delete) to enter the BIOS settings.
   - Verify that the memory (12 GB) and the two hard drives are recognized.
   - Select Exit to boot to the operating system.
   - From the taskbar, select File Explorer.
   - From the left pane, select This PC.
   - Verify that the optical drive is shown.