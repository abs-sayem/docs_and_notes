## **Wifi Connection: An Understanding**

### **How Internet Works in a Home or Office Setup:**
When we buy an internet package from an Internet Service Provider (ISP), they assign a public IP address. This IP is unique and allows our device to connect to the internet.

**Single User Setup:**
- If I am the only user, I can connect my laptop or PC directly to the ISP’s cable using an Ethernet cable.
- This means only one device will have internet access.

**Multiple Users Setup:**
- If multiple people need internet (family, office, etc.), a router is required.
- The router takes the single public IP from the ISP and creates multiple private IPs for different devices.
- Devices can connect wirelessly (Wi-Fi) or wired (via Ethernet and switch).

- **`Ethernet`** *is the cable that connects with our laptop or PC throuth a port (called ethernet port).*
- **`Switch`** *is a device that has multiple ethernet port which allows multiple devices connected through ethernet machanism.*

**Role of a Switch:**
- A switch does not create private IPs like a router. It simply forwards the IPs assigned by the router to multiple devices.
- Some advanced managed switches can handle IP assignments, but they don’t replace a router’s core function.

**Connection Flow of Wifi:**
- ISP Cable → ONU → Router → Devices (via Wi-Fi or Switch)
- The ONU (Optical Network Unit) is the first device that connects to the ISP’s fiber-optic cable.
- The router then distributes the internet to multiple devices.

### **If you wonder:**
**Can we get more than one public IP from ISP with a single package?**
- It depends on the ISP. Some ISPs allow multiple public IPs, but usually, you need to pay extra for each additional IP.
- Most home internet plans provide only one public IP, and the router uses NAT (Network Address Translation) to share it among multiple devices.

**Why does the ISP cable connect to ONU before the router? What is the function of an ONU?**
- The ONU (Optical Network Unit) converts the fiber-optic signals from the ISP into electrical signals that your router can understand.
- Think of it like a translator:
- Fiber-optic signals → ONU → Electrical signals → Router → Devices
- Without an ONU, your router wouldn’t be able to process the internet signal properly.

**Do switches exist that can create private IPs like a router?**
- Standard switches do not create private IPs; they only forward data between devices.
- However, Layer 3 switches can handle IP assignments and routing, but they are more complex and expensive.
- For home or office use, a router is the best choice for managing private IPs.

**What is the difference between Public and Private IP? Why does this concept exist?**
- **`Public IP:`** Assigned by the ISP, unique on the internet, used for external communication.
- **`Private IP:`** Created by a router, used within a local network, not visible on the internet.<br>
`For Example - to Understand Public vs. Private IP:`<br>
Imagine a building with apartments:
- The building address (public IP) is unique and used for deliveries.
- Each apartment number (private IP) is used inside the building for organizing rooms.
- The receptionist (router) ensures that packages (internet data) reach the correct apartment.

**Final Thoughts:**
- ONU is necessary to convert fiber signals.
- Router creates private IPs, while switches only forward them.
- Public IP is like a building address, and private IPs are like apartment numbers.