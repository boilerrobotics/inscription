# Network

<!-- ## Abstract

We use 2 Ubiquiti Rocket M2 for wireless network between the base station and the rover.
By default (or after factory reset), the device IP address will be 192.168.1.20.
It won't serve as DHCP server, therefore, we need to set the computer to a static IP address.
Then open 192.168.1.20 on the browser to changing configurations.
The default username and password are `ubnt`.
As there are two devices, we need to change IP address of one of them.
The recommendation is changing the base station one.

1. Changing IP address to avoid IP duplication.
2. Changing mode of operation from `Base Station` to `Access Point`. -->

## Abstract
We use 2 Ubiquiti Rocket M2 for wireless network between the base station and the rover. This will allow us to connect our device to the rover given long ranges to enable us to complete our mission tasks.

## Initial Configuration
To configure both devices, follow the instruction manual provided. Given that we will use both of them, manually change the IP address of one of them (it is recommended to change the Base Station one). Additionally, change the mode of operation of the Base Station.

To change configurations, open 192.168.1.20 on the browser. The username and password are `ubnt`.
1. To change the IP address, login to the portal and go into the tab labeled  `Network`. Manually set the IP address of the device here.
2. to change the mode of operation of the Base Station, go to the tab labeled `Wireless`, and change the wireless mode to `Access Point`.

## Facilitating Connection 
Now that both devices are properly configured with different addresses, we can now connect them to one another. 
1. Attach an antannae on both devices.
2. Connect a 
3. Connect the `Rover` to a power outlet, and the `Base Station` to a local computer. (it does not matter but for simplicity and preparation for the competition, designate the rover to the actual rover, and the base station to a computer).

## Usage
Ensure that the colors indicated on the devices light up, and experiment different distances and elevations and record outcomes.

## Troubleshooting
Spring 2025 Semester : 
1. One issue that we ran into was not being able to connect both devices. This was because of designating the same port for both devices, and of having an incorrect mode of operation.