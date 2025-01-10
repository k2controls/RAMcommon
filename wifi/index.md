---
layout: default
---

### Summary:
This tutorial covers how to connect your Raspberry Pi to various Wi-Fi access points. The tutorial will guide you through setting up a connection using the NMC_PSK access point, the NMC Guest access point, the Makerspace access point, and your personal phone hotspot.

To test your Internet connectivity on the Raspberry Pi, open a terminal window and enter the following command. This requests a response from the Google name server at IP address 8.8.8.8. You should receive continuous replies showing the response times.

```console
ping 8.8.8.8
```

https://youtu.be/7xUBc1Skaxg

### 1. **NMC_PSK Access Point**:

- The NMC_PSK Wi-Fi access point is provided by NMC and is limited to specific locations, such as the Parsons-Stulen building. Expansion to the Innovation Center is planned.
- This access point is for class-related activities.
- The NMC Student Wi-Fi network and your student credentials will not work on your piRover due to the authentication methods used by NMC.
- Ensure your Pi is connected to the NMC_PSK network if you are within a supported area.
- The required password for NMC_PSK is:

```
Baffle-Amused-Stencil4
```

### 2. **NMC Guest Access Point**:
   - The NMC Guest Wi-Fi access network provides another option for connecting on NMC's campus but requires an extra step when connecting.
   - To use this network, open your browser after connecting to the NMC guest network and enter nmc.edu in the browser's address bar. You are redirected to the NMC Guest policies page. Click the button at the bottom of the page to accept NMC policies. Verify your connectivity using the ping operation provided above.

### 3. **Makerspace Wi-Fi Access Point**:
   - The Makerspace offers a Wi-Fi network, but it is limited to the Makerspace area. 
   - Look for 'makerspace1' or 'makerspace5g' in the available networks list. No password is required."
   - The strength of the Wi-Fi signal may vary, and students have reported some connectivity issues.
   - While this option is available, it might not be the most reliable for stable connections.

### 4. **Phone Hotspot Access**:
   - Using your phone as a hotspot is a flexible option for connecting your Raspberry Pi to the internet.
   - Simply turn on your phone's hotspot feature and connect your Pi to it just like any other Wi-Fi network.
   - This option works anywhere, provided you have a mobile data connection.
   - An added advantage is that many cell phone hotspot application display the IP address for connected devices. You can use this IP address instead of the piRover hostname when connecting remotely via TigerVNC.
   - Please note that using your phone as a hotspot may consume significant data, especially when working with larger downloads or updates. You'll be fine completing class activities but be sure to be connected to a non-metered connection when installing updates or applications on the Raspberry Pi.
