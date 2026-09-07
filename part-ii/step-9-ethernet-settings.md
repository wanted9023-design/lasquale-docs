# Step 9: Ethernet Settings

#### Step 1: Open Adapter Settings

* Press **Win + R**, type `ncpa.cpl`, and press **Enter** to open Network Connections.

#### Step 2: Modify Ethernet Properties

* Right-click your Ethernet connection and select **Properties**.

#### Step 3: Select Only These Two Options

* In the Properties window, make sure **only** the following two options are checked (scroll down to disable the other ones):
  * **QoS Packet Scheduler**
  * **Internet Protocol Version 4 (TCP/IPv4)**
* Click **OK**.

#### Step 4: Configure Advanced Settings

* Right-click your Ethernet connection again, select **Properties**, then click **Configure**.
* Go to the **Advanced** tab and apply these changes:

  * **Advanced EEE:** Disabled
  * **ARP Offload:** Disabled
  * **Flow Control:** Disabled
  * **IPv4 Checksum Offload:** Disabled
  * **Large Send Offload v2 (IPv6):** Disabled
  * **Network Address:** Not Present
  * **TCP Checksum Offload (IPv6):** Disabled
  * **UDP Checksum Offload (IPv6):** Disabled

{% hint style="info" %}
If any option is not available, just skip it.
{% endhint %}

#### Step 5: Restart Your PC

* After applying these settings, restart your computer for changes to take effect.

#### Step 6: Apply Network Settings

* After restarting your PC, download networksettings.bat
* Run it as **Administrator** and follow the on-screen instructions carefully.

#### Step 7: VPN Setup

{% hint style="warning" %}
Some games may require a **different VPN** setup depending on their anti-cheat, more information on Post Spoofing!
{% endhint %}

* Download and install the VPN from [here](https://one.one.one.one/).
* Select 1.1.1.1 with WARP
* Enable the VPN
