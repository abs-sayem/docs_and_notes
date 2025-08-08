# Used Laptop Buying Guide

1. **Laptop Cosmetic:** Check the entire body if there are any major dents or anything broken.
2. **Battery Health:**
    - Open the terminal(admin) or powershell (admin) and run the command **`powercfg /batteryreport`**. It will generate a battery report in the user profile.
    - More than **100 Cycle Count** should be avoided.
    - **10K Full Charge Capacity** is considered for an hour backup. Full Charge Capacity - 33K means it should backup for more than 3 hours.
3. **System Information:**
    - Search for **`System Information`** and open it. It is the default system information checking app for windows.
4. **Keyboard:** (spent at least 5 minutes)
    - Open a text editor and check all the keys are prefectly working.
    - Can check by using any online keyboard checker.
5. **Ports:** (USB, Audio, HDMI) Carry the relatable accessories (like - pendrive, earphone) to check them.
6. **Drive Health:**
    - Open Powershell as Administrator and run:
        ```
        Get-PhysicalDisk | Select FriendlyName, HealthStatus, OperationalStatus
        ```
    - Use portable **`Crystal Disk Info`** or **`HD Sentinel`** application for more details.
7. **CPU and GPU:**
    - Portable apps like **`CPU-Z`** for cpu and **`GPU-Z`** for gpu.
    - Windows default **`System Information`** app have a certain level of information as well.
8. **Date of Purchase:** Check online using laptop's serial number if warrenty is claimed.