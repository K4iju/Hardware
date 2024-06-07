## Scenario

You work at a computer repair store. A customer brought in a computer and asked you to upgrade the motherboard. You replaced the motherboard with a newer model, but now the computer will not boot. In addition to the new motherboard, the computer currently contains the following:

- Intel i7-960 processor

- 12 GB of DDR3 memory

- Two SATA hard drives (one with the operating system installed, and the other with a single volume for storing data)

- A single SATA optical drive


### Steps to Resolve

![Failed](https://github.com/K4iju/Hardware/assets/159083256/c5c3318e-f804-4a5c-8af8-6cdd9835ee17)

1. **Attempt to Power On the Computer**
   - On the computer, select the power button.
   - Select OK to close the prompt indicating that the computer failed to run.
   - This is most likely due to the computer not getting power.

![Female connector](https://github.com/K4iju/Hardware/assets/159083256/630319f7-19a1-49f1-b62b-c37d4da8e291)

2. **Provide Power to the Computer**
   - Above the computer, select Back.
   - Select the AC Power Connector (Female) that is currently plugged into the power supply.
   - Notice that the other end is not connected.
   - From the Selected Component pane, drag the AC Power Connector (Male) to an open outlet on the wall plate.
   - Above the computer, select Front and then select the power button.

![Failed](https://github.com/K4iju/Hardware/assets/159083256/c5c3318e-f804-4a5c-8af8-6cdd9835ee17)
3. **Check if the Computer Powers On**
   - The computer still won't start.
   - Select OK to close the prompt.

![panel](https://github.com/K4iju/Hardware/assets/159083256/6f201704-9820-4cf9-9d46-4d43ea248fa9)


4. **Connect the Case's Power Switch to the Motherboard Header**
   - Above the computer, select Motherboard.
   - Notice that under Partial Connections for the computer, the system case is shown.
   - Under Partial Connections for the computer, select the system case.
   - From the Selected Component pane, drag the Connector, Case, Power Switch to the motherboard header (bottom right).
   - If needed, view the motherboard details to find the connection areas.
   - Above the computer, select Front and then select the power button.

![image](https://github.com/K4iju/Hardware/assets/159083256/8c5ba5ba-0658-459a-abf2-ce8ed920c552)
![image](https://github.com/K4iju/Hardware/assets/159083256/232e688a-3ddb-47f8-85a6-fb3054c13a9a)


5. **Check if the Computer Boots**
   - The computer boots to Windows, but soon powers off. This is typically caused by the computer overheating.
   - Select OK to close the prompt.
![image](https://github.com/K4iju/Hardware/assets/159083256/a1c3bf1c-0d1e-48bd-8004-944bb9dab291)

6. **Provide Power to the Heat Sink and Fan**
   - Above the computer, select Motherboard.
   - Notice that, under Partial Connections for the computer, the heat sink and fan is shown.
   - Under Partial Connections for the computer, select the heat sink and fan.
   - From the Selected Component pane, drag the Connector, Fan, CPU 4-pin that is connected to the motherboard (top center).
   - Above the computer, select Front.
   - On the computer, select the power button.
   - The computer powers on and stays on.
![image](https://github.com/K4iju/Hardware/assets/159083256/4be5ace2-677b-45b3-a4c0-1085f694908f)

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
