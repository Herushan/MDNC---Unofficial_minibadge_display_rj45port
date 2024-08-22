# Unofficial_minibadge_display_rj45port
Unofficial port for minibadge displays to interconnect to share power and I2C between minibadge display boards. This was done on my own as I did not want to use the official minibadge 20 pin board to board connector for minibadges.

**** WARNING ******
Do not connect two power sources to the same board at the same time. The USB-C power should only be on one of the boards that then powers the others through the rj45 port.
*******************

I wanted a connector that can use ethernet cable that I had around to connect display boards and make it possible to adapt for unique tesselation of the dsiplay boards as well. This came to reality in 2023 with my first set of 4x4 minibadge display boards that can only be powered by one power source and it sends 5V, GND, SCL, and SDA over the ethernet cable.

The pinout for the ethernet jack is as shown:
![image](https://github.com/user-attachments/assets/cfba36b3-be9d-4d74-b0de-3a3780ca7eea)

Pin 1: SDA
Pin 2: SCL
Pin 3: NC
Pin 4: + 5V
Pin 5: + 5V
Pin 6: NC
Pin 7: GND
Pin 8: GND

This is a novalty connector and one I plan to use for display boards and other add-ons with minibadges.

