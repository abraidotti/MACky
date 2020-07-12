# MACky
MACky - a mac address changer

Change a MAC address of any non-virtual interface

Based on Zaid Sabih's tutorial in <https://www.udemy.com/course/learn-python-and-ethical-hacking-from-scratch>

## Table of Contents  
[Requirements](##Requirements)  
[Installation](##Installation)  
[Configuration](##Configuration)  
[Execution](##Execution)  
[Contribution](##Contribution)  

## Requirements

- Python 3

- a non-virtual network interface

## Installation

```bash
git clone https://github.com/abraidotti/MACky
cd MACky
```

## Configuration

None

## Execution

Example interface: eth0

Example MAC address: 11:22:33:44:55:66

```bash
python3 MACky.py --interface eth0 --mac 11:22:33:44:55:66
```

## Contribution

If you'd like to contribute, file a pull request or github issue to discuss.

TODO:

- on execution with no flags, offer a menu of non-virtual interfaces and a MAC input