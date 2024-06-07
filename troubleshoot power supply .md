# Lab Instructions: Power Supply Testing and Replacement

## Objective
Complete this lab to test and replace the power supply of a computer.

## Steps

### 1. Test the Computer
1. Turn on the computer and observe the symptoms.
2. You are informed that the computer has shut down.
3. Select **OK** to close the message.

### 2. Add Power Supply Tester to Workspace
![PST](https://github.com/K4iju/Hardware/assets/159083256/9b349372-f1ca-4c34-ba81-9c670f9bf848)

1. Expand **PC Tools** under the **Shelf**.
2. Drag the **Power Supply Tester** from the **Shelf** to the **Workspace** area.

### 3. Test the Power Supply
![old pst](https://github.com/K4iju/Hardware/assets/159083256/0b1accd1-d6db-4905-ad45-822ba681c27e)
* Voltages are below 12V *

1. Select **Motherboard** above the computer to switch to the motherboard view.
2. Select the power supply.
3. Notice the two cables connected from the power supply to the motherboard are highlighted.

4. ![disconnect SATA](https://github.com/K4iju/Hardware/assets/159083256/96a32d9a-2dbf-4f1d-8c0a-2437d74f67bf)

5. From the motherboard, drag the **Connector, Power Supply, 20+4 pin power supply connector** to the far-right port on the power supply tester.
6. From the motherboard, drag the **Connector, Power Supply, 4-pin CPU power connector** to the 4/6/8 (upper-left) port on the power supply tester.
7. From the **Selected Component** pane, drag an unconnected **Connector, SATA 15-pin power connector** to the bottom-left port on the power supply tester.
8. Observe the lights and values on the Power Supply Tester.
9. Conclusion: The power supply is bad.

### 4. Remove the Power Supply
1. Select **Back** above the computer to switch to the back view of the computer.
2. Drag the power cord from the computer's power supply to the **Workspace**.
3. Select **Drive Bays** above the computer to switch to the drive bays view.
4. Drag the power connector (top left) from the optical drive to the **Workspace**.
5. Drag the power connector (bottom left) from the SATA drive to the **Workspace**.
6. Disconnect all connectors from the power supply tester.
7. Select **Motherboard** above the computer to switch to the motherboard view.
8. Drag the power supply to the **Workspace** area.

### 5. Install a New Power Supply
![New PST](https://github.com/K4iju/Hardware/assets/159083256/27233bc7-0372-4ab9-bfe3-4e89f267f987)

1. Expand **Power Supplies** under the **Shelf**.
2. Drag the **Power Supply, ATX, 20+4 pin, PCIe power supply** to the correct area in the computer.
3. From the **Selected Component** pane, drag the **Connector, Power Supply, 20+4 pin power supply connector** to the motherboard connector to connect the motherboard main power connector.

![CPS](https://github.com/K4iju/Hardware/assets/159083256/dc3760a0-d8db-4b11-aaba-4c6ece6d8c5f)

5. From the **Selected Component** pane, drag the **Connector, Power Supply, 4-pin CPU power connector** to the motherboard connector.

### 6. Connect the SATA Hard Drive and Optical Power
1. Select **Drive Bays** above the computer to switch to the drive bays view.
   ![S15PC](https://github.com/K4iju/Hardware/assets/159083256/2ad49f12-9e9d-4cdd-8294-b4be3d41d7b7)

2. From the **Selected Component** pane, drag an unconnected **Connector, SATA 15-pin power connector** to the location on the optical drive.
3. From the **Selected Component** pane, drag an unconnected **Connector, SATA 15-pin power connector** to the location on the hard drive.

### 7. Provide Power to the Computer and Test
1. Select **Back** above the computer to switch to the back view of the computer.
2. Under **Partial Connections** for the wall plate, select the power cord.
 ![FPC](https://github.com/K4iju/Hardware/assets/159083256/82a3db6f-964c-4a3f-8ab5-05414af19b39)

3. From the **Selected Component** pane, drag the **AC Power Connector (Female)** to the power supply port.
4. On the power supply, select the power supply switch to turn it to the **on** position.
5. Select **Front** above the computer to switch to the front view.
6. On the computer, select the power button to turn on the computer and verify that the computer boots into Windows.

## Conclusion
![NPST](https://github.com/K4iju/Hardware/assets/159083256/633d72af-d6a2-4fe0-9677-dc2a68348a25)

Following these steps will help you to properly test and replace a faulty power supply in a computer.
![end result](https://github.com/K4iju/Hardware/assets/159083256/1b3adcf7-e646-42b0-a74c-4322813f9a5e)
