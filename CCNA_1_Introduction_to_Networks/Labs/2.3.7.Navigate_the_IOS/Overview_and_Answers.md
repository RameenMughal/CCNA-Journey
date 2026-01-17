# 2.3.7 Packet Tracer - Navigate the IOS

## Objectives

- Part 1: Establish Basic Connections, Access the CLI, and Explore Help 
- Part 2: Explore EXEC Modes
- Part 3: Set the Clock

## Background / Scenario

In this activity, you will practice skills necessary for navigating the Cisco IOS, such as different user access 
modes, various configuration modes, and common commands used on a regular basis. You will also practice 
accessing the context-sensitive Help by configuring the clock command.

## Instructions

### Part 1: Establish Basic Connections, Access the CLI, and Explore Help

#### Step 1: Connect PC1 to S1 using a console cable.

<img width="95" height="119" alt="image" src="https://github.com/user-attachments/assets/61b09e21-2b3c-4288-926b-6af17138f131" />

#### Step 2: Establish a terminal session with S1.

**Question**: Click the Terminal application icon. Verify that the Port Configuration default settings are correct. 

What is the setting for bits per second?

**Answer**: 9600 bits per second.

<img width="518" height="184" alt="image" src="https://github.com/user-attachments/assets/93c71309-4c63-4933-891f-af1064b69599" />

---

**Question**: The screen that appears may have several messages displayed. Somewhere on the screen there should 
be a Press RETURN to get started! message. Press ENTER.

What is the prompt displayed on the screen?

**Answer**: `S1>`

<img width="158" height="53" alt="image" src="https://github.com/user-attachments/assets/723dd2b7-1caf-4b35-9bcd-68d3f86df1dd" />

#### Step 3: Explore the IOS Help.

**Question**: The IOS can provide help for commands depending on the level accessed. The prompt currently displayed is called User EXEC, and the device is waiting for a command. The most basic form of help is to type a question mark (?) at the prompt to display a list of commands.

```
S1> ?
```

Which command begins with the letter ‘C’?

**Answer**: `connect`

<img width="286" height="167" alt="image" src="https://github.com/user-attachments/assets/aa28b3aa-9c0b-46c4-ab6a-d4a923b04dd7" />

---

**Question**: At the prompt, type t and then a question mark (?). 

```
S1> t?
```

Which commands are displayed?

**Answer**: `telnet`, `terminal` and `traceroute`

<img width="154" height="32" alt="image" src="https://github.com/user-attachments/assets/5088175a-03cd-4c36-b040-53e28790d96e" />

---

**Question**: At the prompt, type te and then a question mark (?). 

```
S1> te?
```

Which commands are displayed?

**Answer**: `telnet` and `terminal`

<img width="87" height="32" alt="image" src="https://github.com/user-attachments/assets/6e31d428-df1b-4ec4-a4ab-a7df360d3e57" />

### Part 2: Explore EXEC Modes

In Part 2 of this activity, you will switch to privileged EXEC mode and issue additional commands

#### Step 1: Enter privileged EXEC mode.

**Question**: At the prompt, type the question mark (?).

```
S1> ?
```

What information is displayed for the enable command?

**Answer**: Turn on privileged commands.

<img width="289" height="150" alt="image" src="https://github.com/user-attachments/assets/c234c62e-f77a-4c59-b935-5da62ab81762" />

---

**Question**: Type `en` and press the Tab key.

```
S1> en<Tab>
```

What displays after pressing the Tab key?

**Answer**: `enable`

<img width="70" height="24" alt="image" src="https://github.com/user-attachments/assets/c04787d4-3c36-4cc0-bda8-021b54f86b5b" />

---

**Question**: What would happen if you typed `te<Tab>` at the prompt?

**Answer**: There are more than one commands (`terminal` and `telnet`) that has `te` so it does not return anything as there should be only one command to use the Tab

<img width="46" height="24" alt="image" src="https://github.com/user-attachments/assets/0bba58c2-bc67-41f3-801d-ae4b05ed9bcd" />

---

**Question**: Enter the `enable` command and press ENTER.

How does the prompt change?

**Answer**: The prompt changes from `S1>` to `S1#`.

<img width="64" height="22" alt="image" src="https://github.com/user-attachments/assets/cfb79ab5-fcf5-4fee-bd2c-238405676a16" />

---

**Question**: When prompted, type the question mark (?).

```
S1# ?
```

One command starts with the letter ‘C’ in user EXEC mode.

How many commands are displayed now that privileged EXEC mode is active? (Hint: you could type `c?` to list just the commands beginning with ‘C’.)

**Answer**: `clear`, `clock`, `configure`, `connect` and `copy`.

<img width="380" height="293" alt="image" src="https://github.com/user-attachments/assets/14f7e665-b3c7-4323-92cb-93163d64bd91" />

#### Step 2: Enter Global Configuration mode

**Question**: When in privileged EXEC mode, one of the commands starting with the letter ‘C’ is `configure`. Type either  the full command or enough of the command to make it unique. Press the <Tab> key to issue the command and press ENTER.

```
S1# configure 
```

What is the message that is displayed? 

**Answer**: Configuring from terminal, memory, or network [terminal]?

<img width="297" height="23" alt="image" src="https://github.com/user-attachments/assets/4a2cd200-9eaa-421b-a13a-71898b15db48" />

---

**Question**: Press Enter to accept the default parameter that is enclosed in brackets `[terminal]`. 

How does the prompt change?

**Answer**: Thr prompt changes from Privileged EXEC Mode to Global Config Mode

<img width="311" height="43" alt="image" src="https://github.com/user-attachments/assets/c84a6d47-f2ea-40d4-ad24-a88281c306df" />

---

### Part 3: Set the Clock

#### Step 1: Use the clock command. 

**Question**: Use the `clock` command to further explore Help and command syntax. Type `show clock` at the privileged EXEC prompt. 

```
S1# show clock
```

What information is displayed? What is the year that is displayed?

**Answer**: Year 2035

<img width="175" height="32" alt="image" src="https://github.com/user-attachments/assets/8a65ade8-ec82-48c6-aa8e-0cdeb9930661" />

---

**Question**: Use the context-sensitive help and the `clock` command to set the time on the switch to the current time. Enter the command `clock` and press ENTER. 

```
S1# clock<ENTER>
```

What information is displayed?

**Answer**: Incomplete command

<img width="114" height="32" alt="image" src="https://github.com/user-attachments/assets/cd775b16-5f09-4baa-ac87-3f6562830524" />

---

**Question**: The “% Incomplete command” message is returned by the IOS. This indicates that the `clock` command needs more parameters. Any time more information is needed, help can be provided by typing a space after the command and the question mark (?). 

```
S1# clock ?
```

What information is displayed?

**Answer**: `set` command is needed with the `clock`

<img width="145" height="35" alt="image" src="https://github.com/user-attachments/assets/296621a4-2e4c-4333-82f3-26638e148b5a" />

---

**Question**: Set the clock using the clock set command. Proceed through the command one step at a time.

```
S1# clock set ?
```

What information is being requested?

**Answer**: Current Time is being requested.

<img width="133" height="32" alt="image" src="https://github.com/user-attachments/assets/7bd23bd4-0d69-4340-85da-d1f0b578941c" />

---

**Question**: What would have been displayed if only the `clock set` command had been entered, and no request for help 
was made by using the question mark?

**Answer**: Incomplete command.

<img width="116" height="32" alt="image" src="https://github.com/user-attachments/assets/3608cb43-586e-4b3e-8b97-5f7abf8cbbbc" />

---

#### Step 2: Explore additional command messages.

**Question**: `S1# cl<tab>` What information was returned?

**Answer**: `clear` and `clock` commands

<img width="70" height="36" alt="image" src="https://github.com/user-attachments/assets/55f7cc37-75e7-4cc1-8260-92a163277e09" />

---

**Question**: `S1# clock` What information was returned?

**Answer**: Incomplete command.

<img width="117" height="32" alt="image" src="https://github.com/user-attachments/assets/2306faf6-10b0-400a-b823-3b97a3a68e41" />

---

**Question**: `S1# clock set 25:00:00` What information was returned?

**Answer**: Invalid input as range is only 0 - 24 hour format.

<img width="200" height="51" alt="image" src="https://github.com/user-attachments/assets/7b9ebb68-ab35-4569-af45-be22e0e25889" />

---

**Question**: `S1# clock set 15:00:00 32` What information was returned?

**Answer**: Invalid input as range is only 1 - 31 days maximum.

<img width="205" height="50" alt="image" src="https://github.com/user-attachments/assets/eef60473-7f3a-41ac-ac22-042f17cdb8cb" />
