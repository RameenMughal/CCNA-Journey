# 2.3.8 Packet Tracer - Navigate the IOS Using a Terminal Client for Console Connectivity - Physical Mode

## Objectives
- Part 1: Access a Cisco Switch through the Serial Console Port
- Part 2: Display and Configure Basic Device Settings
- Part 3: Access a Cisco Router Using a Mini-USB Console Cable

## Background / Scenario

In this Packet Tracer Physical Mode (PTPM) activity, you will learn how to access a Cisco device via a direct local connection to the console port, using the generic terminal emulation program in Packet Tracer. After you have established a console connection with the Cisco device, you can display or configure device settings. In this activity, you will only display settings and configure the clock in this lab.

<img width="623" height="377" alt="image" src="https://github.com/user-attachments/assets/bdb0bade-a68a-4456-80c8-62c58f04c1ae" />

## Instructions

### Part 1: Access a Cisco Switch through the Serial Console Port

In this part, you will connect a PC to a Cisco switch using a rollover console cable. This connection will allow 
you to access the CLI and display settings and configure the switch.

#### Step 1: Install and investigate a 2960 switch.

1. There are several switches, routers, and other devices on the Shelf. Click and drag the 2960 to the Rack. In Packet Tracer, most devices that you drag to the Rack or the Table are automatically connected to power. Some devices require that you turn on the power. However, a 2960 switch powers up as soon as you move it to the Rack. 

<img width="130" height="168" alt="image" src="https://github.com/user-attachments/assets/aef0ec99-b576-4f7d-863e-519fdbd2e1f1" />

2. Right click the 2960 switch and select Inspect Front. Use the zoom tool to get a better view. Notice that there are 24 ports to connect users and two additional ports to connect the switch to other switches or routers.

<img width="378" height="80" alt="image" src="https://github.com/user-attachments/assets/1deb60a9-7a86-4907-8d3d-0149e3762066" />

3. Click the X to close the Inspect Front view.

4. Right click the 2960 switch and select Inspect Rear. Use the zoom tool to get a better view. Notice that there is a CONSOLE port for connecting a rollover cable to a PC.

<img width="523" height="104" alt="image" src="https://github.com/user-attachments/assets/a4055ddd-bf74-45e3-a6e3-28a2f22355f3" />

5. Click the X to close the Inspect Rear View.

#### Step 2: Install and investigate the PC.

1. Click and drag the PC to the Table.

<img width="502" height="243" alt="image" src="https://github.com/user-attachments/assets/b1a40b82-9035-4be1-93e2-967974c378a5" />

2.  Right click the PC and select Inspect Front. Click the red power button to turn on the PC. You should now see a green light on the front of the PC. At the bottom of the PC, notice that there is a Fast Ethernet interface. Next to it is an RS 232 port for connecting a rollover cable. Below these are two USB ports that can also be used for console access.

<img width="277" height="274" alt="image" src="https://github.com/user-attachments/assets/79516f58-3d33-4316-b958-c7b46b81fbcb" />

#### Step 3: Connect the switch and PC using a rollover console cable

<img width="221" height="349" alt="image" src="https://github.com/user-attachments/assets/1cbf2403-a78e-4ba2-ae02-0e90b252c5f5" />

#### Step 4: Configure the Packet Tracer Terminal program to establish a console session with the switch.

1. Click PC > Desktop tab > Terminal. The default parameters for the console port are 9600 baud, 8 data bits, no parity, 1 stop bit, and no flow control. The Terminal default settings match the console port settings for communications with the Cisco IOS on the switch.

<img width="520" height="177" alt="image" src="https://github.com/user-attachments/assets/3a42856a-d93e-42a4-95b5-8c7862b1f26c" />

2. Click OK. The last line in the terminal output should be Press RETURN to get started!.

<img width="493" height="124" alt="image" src="https://github.com/user-attachments/assets/8741035b-0f21-45fc-af76-e976ac2e438d" />

3. Press the ENTER key to get to the User EXEC mode switch prompt.

<img width="416" height="86" alt="image" src="https://github.com/user-attachments/assets/0298c33f-b222-4e95-8ec3-eccbb61c3313" />

### Part 2: Display and Configure Basic Device Settings

In this part, you are introduced to the user and privileged EXEC modes. You will determine the IOS version, display the clock settings, and configure the clock on the switch.

#### Step 1: Display the switch IOS image version.

While you are in the user EXEC mode, use the show version command to display the IOS version for the switch.
Switch> show version

**Question**: Which IOS image and version is currently in use by the switch?

**Answer**: 

<img width="489" height="367" alt="image" src="https://github.com/user-attachments/assets/d46e3755-563b-4ba9-af86-553bb881f0e5" />














