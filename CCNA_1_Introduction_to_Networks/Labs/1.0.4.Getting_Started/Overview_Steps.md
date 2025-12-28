# Getting Started in Cisco Packet Tracer 

This practical is taken from **1.0.4 Video - Getting Started in Cisco Packet Tracer**

After exploring Cisco Packet Tracer, then creating first Cisco Packet Tracer Network

Building network in the Logical Topology.

Starting by choosing the router, a ISR4331 Cisco Router.

In the Switch category, taking first switch that is 2960-24TT Switch

We will be connecting two or more end devices, so selecting the End Devices catgeory, taking one PC-PT and Laptop-PT

<img width="254" height="149" alt="image" src="https://github.com/user-attachments/assets/5da014e5-55e8-48ca-9ee2-743c1daf4c9e" />

Then interconnecting these by using cabling. This is under Connections Category.

Selecting the Copper-Straight Through wire to connect the PC to the Switch.

Taking the wire to the PC, will have some options, choose FastEthernet0. Then connect it to the switch and will have many options to select, any options can be chosen, I am choosing FastEthernet0/1.

Repeat the same process for Laptop by connecting it to the switch. Choose FastEthernet0 from the Laptop and then choose any option from the Switch, I am choosing FastEthernet0/2.

<img width="239" height="148" alt="image" src="https://github.com/user-attachments/assets/0612fd8b-6265-4101-a46c-3cb3ae0cf5fc" />

Lastly to connect the switch to the router, Take the same cable Copper-Straight Through. From the Switch choose GigabitEthernet0/1 and from the Router choose GigabitEthernet0/0/0

<img width="231" height="161" alt="image" src="https://github.com/user-attachments/assets/377650f5-8061-4835-9291-4df66b4cc9c2" />

This is the Logical Topology on how the devices are connected to each other. Let's see it Physical View by clicking the device and the first thing you see is the device

<img width="515" height="335" alt="image" src="https://github.com/user-attachments/assets/8238c276-c6d6-47a9-9df6-cf0e5e38c96b" />

Also in the Physical Toplogy you can see the connections by clicking the area to get closer as first you see Home City then Corporate Office then see your devices.

<img width="371" height="254" alt="image" src="https://github.com/user-attachments/assets/7df08b12-9224-432e-a3d3-6623691d84f7" />

<img width="296" height="290" alt="image" src="https://github.com/user-attachments/assets/cc92de35-6bb2-405b-a5c0-e8865ff9d9ad" />

We can also lower the router and switch.

<img width="296" height="269" alt="image" src="https://github.com/user-attachments/assets/beb2960a-1c4f-4c70-ae61-266c1e1d8e91" />

By right clicking the wire of Laptop of PC, we get three options:
- Manage cable -> To organize the cables for clean space and security
- Color cable -> To distinguish from other wires
- Delete cable -> To delete the wire connection

By right clicking the switch, we get five options:
- Inspect Front - Check the front view
- Inspect Rear - Check the back view
- Delete Device - Delete the device and its connections completely.
- Manage All Cables on Device - Organize the cables of switch for clean space
- Unmanage All Cables on Device - Get back to the state when the cables were not managed or organized.

When choosing Manage All Cables on Switch Device, it looks like that the wires connecting all the devices disappeared but it organized the cables to keep it nice and tidy.

<img width="280" height="252" alt="image" src="https://github.com/user-attachments/assets/e36215ea-976a-406b-9b79-dcf9698f2da5" />

You can get back to the unoragnized state by choosing Unmanage All Cables on Switch Device

<img width="269" height="266" alt="image" src="https://github.com/user-attachments/assets/56550c29-f4a8-41d7-bffe-461faf995571" />

We can see the front of the switch by choosing Inspect Front. This shows the front view and can see details of each port by hovering it over like the PC is connected to the Switch by Source Port FastEthernet0/1 and Dest Device is PC0.

<img width="514" height="104" alt="image" src="https://github.com/user-attachments/assets/63f43c8b-435c-48a7-b324-76df88d84a8b" />

We can see the back of the switch by choosing Inspect Rear and see Console which is the initial configuration setup of the switch and there is no power button as Cisco Switch automatically powers on when it is connected through the cable.

<img width="515" height="104" alt="image" src="https://github.com/user-attachments/assets/af365e72-4fbc-4798-a52c-07fb62c60609" />

We can see the Front view of the Router by choosing Inspect Front.

<img width="516" height="101" alt="image" src="https://github.com/user-attachments/assets/fc381ea4-9f9d-4c3e-a277-74a200a49033" />

Checking the back view of the Router by choosing Inspect Rear. We see Console, AUX and Management Port. It also contains Power button where we can on and off the Router.

The AUX port on a router, often called the auxiliary port, is a serial port primarily used for remote management and administration of the router, especially when the primary network connection is unavailable.

<img width="515" height="101" alt="image" src="https://github.com/user-attachments/assets/ab7e6a50-379e-4d02-8912-3825229edd8a" />

If we want to deploy new device in the Physical Toplogy, we can select the Server from the End Device Catgeory and put in the Network space.

<img width="263" height="276" alt="image" src="https://github.com/user-attachments/assets/be11bc0e-ff68-4165-86d7-29ec74315725" />

It is powered on and has interfae that can be connected to the switch. Taking the Copper-Straight Through cable from the Connections Category. 

Take the wire and click on the interface of the Server which is FastEthernet0 and then click on any port of the switch, I am choosing FastEthernet0/3. You can take a closer look on the ports by right clicking the switch and choosing the Inspect Front and click the cable on any port you like.

You can change the color of the cable if the cables are mixed up.

<img width="277" height="279" alt="image" src="https://github.com/user-attachments/assets/2533d768-7281-43d3-8223-9d191fd05d60" />


<img width="242" height="204" alt="image" src="https://github.com/user-attachments/assets/2a8236ad-bd96-466e-8528-53ef281ab2d2" />



