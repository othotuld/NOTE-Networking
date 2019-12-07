# How to install Microsoft loopback adapter on windows 10

- Open Device manager
    - "Windows + X" and select Device Manager
    - or "Windows + R" to open the Run dialog and then type "devmgmt.msc" to open Device Manager
    - or any of your favorite way to open it
- Click on your PC root node or any child nodes of your PC (This will let the menu on next step showing up)
- On menu, select Action -> Add legacy hardware
- "Add hardware Wizard" will pop up, Click Next
- Select "Install the hardware that I manually select from a list (Advanced)" and then click Next
- Find "Network adapters", select and click Next
- For Manufacturer/Model, Select "Microsoft"/"Microsoft KM-TEST Loopback Adapter" and Next
- Next again to install and then Finish
- Open "Network Connections" control panel to check your new loopback card
    - "Windows + R" and type "ncpa.cpl"
    - or any of your favorite way to open it
