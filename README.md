# Unofficial_minibadge_display_rj45port
Unofficial port for minibadge displays to interconnect to share power and I2C between minibadge display boards. This was done on my own as I did not want to use the official minibadge 20 pin board to board connector for minibadges. Still need to think of a cool short name for this but for now it can also be call the minibadge display network connector or MDNC.

**** WARNING ******
Do not connect two power sources to the same board at the same time. The USB-C power should only be on one of the boards that then powers the others through the rj45 port.
*******************

I wanted a connector that can use ethernet cable that I had around to connect display boards and make it possible to adapt for unique tesselation of the dsiplay boards as well. This came to reality in 2023 with my first set of 4x4 minibadge display boards that I added the MDNC that sends 5V, GND, SCL, and SDA over the ethernet cable.

The pinout for the MDNC ethernet jack is as shown:
![image](https://github.com/user-attachments/assets/cfba36b3-be9d-4d74-b0de-3a3780ca7eea)

Pin 1: SDA
Pin 2: SCL
Pin 3: NC
Pin 4: + 5V
Pin 5: + 5V
Pin 6: NC
Pin 7: GND
Pin 8: GND

![PXL_20231123_185848067](https://github.com/user-attachments/assets/52268a6d-ac93-489f-8e2a-610ac995038e)
![PXL_20231123_185828914](https://github.com/user-attachments/assets/847aba0e-a599-4926-bb4a-3707a7cb4bf6)


This is a novalty connector and one I plan to use for display boards and other add-ons with minibadges. I also wanted the possiblity to use the USB to rj45 serial cables that come with UPS with the boards as well for possible communication witht he I2C minibadges.

