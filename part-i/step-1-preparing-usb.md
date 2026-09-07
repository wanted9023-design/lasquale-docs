# Step 1: Preparing USB

1. Download Media Creation Tool
2. Open **Media Creation Tool.**
3. Select **Create installation media (USB flash drive, DVD or ISO file) for another PC.**
4. Use the recommended options.
5. Select **USB flash drive** *(min 8 GB).*
6. Select your USB flash drive *(this will remove all its data).*
7. Drag this file (Autounattended.xml): Together with the windows

### Your USB should look like:

*(Insert screenshot)*

#### Getting Ethernet Drivers

1. Open **Device Manager**
2. Head over to Network Adapters
3. **Download the correct driver based on your result:**
   * **Realtek Ethernet:**
     Download Realtek Ethernet Driver
4. **Extract the downloaded drivers to your USB stick**
   You'll need them later during the reinstall process.

{% hint style="info" %}
ASUS Motherboards:
* Make sure you downgrading to a version **PRE 2022**
* If you have the **lowest version** without any possibility to downgrade further, then you may proceed to **upgrade by only one version**.
{% endhint %}

### Prepare BIOS Flash

{% hint style="warning" %}
**Warning:** Incorrect BIOS flashing can damage your system. Proceed at your own risk. Ensure you have the correct BIOS version and a stable power source. Ask the support for help if needed!
{% endhint %}

#### Identify Motherboard

1. Open System Information
2. Look for `BaseBoard Product` and `BaseBoard Manufacturer`.

{% hint style="info" %}
If your system information is corrupted (shows wrong details) or you're unsure please check your BIOS > EZ Mode, For that open **CMD** as **ADMIN** and type `shutdown /r /fw /t 0`
{% endhint %}

1. Search for your Mainboard and Manufacturer, for example: ASUS PRIME B550-PLUS
2. Open the manufacturer site and go to Downloads / Support section.
3. Go to `BIOS` and download the correct BIOS version. (For ASUS PRE 2022)
4. Extract BIOS File to the USB (On ASUS first run the `BIOS Renamer.exe` and then extract the .CAP to the USB)
