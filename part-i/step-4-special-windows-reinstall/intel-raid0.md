# Intel (RAID0)

#### Download Drivers & Extract Drivers

#### Enabling the RAID mode

1. Restart your computer and enter the BIOS again.
2. Locate following options and set them to following value:

**To Locate your SATA Mode:**

**Go to advanced mode in bios:**

We are looking for 'SATA Mode' alongside 'M.2 Storage Raid Support'

There are a few possibilities as where it could be:

1. Advanced Mode -> PCH Storage Configuration - Most Common
2. Advanced Mode -> Storage Configuration
3. Advanced Mode -> Onboard Devices/Integrated Peripherals -> VMD Controller
4. Advanced Mode -> VMD Controller
5. Advanced Mode -> SA (System Agent) -> VMD Controller
6. Advanced Mode -> Onboard Devices/Integrated Peripherals

{% hint style="info" %}
If there is a "VMD Controller" option, enable it. Ignore the below section.
{% endhint %}

Once found:

1. Set `SATA Mode/controller` -> `[ RAID mode / RST Controlled / Optane Mode]`
2. Set `M.2_1 RST PCIE Storage Raid Support` -> `[ Enabled / RST Controlled]`
3. Set `M.2_2 RST PCIE Storage Raid Support` -> `[ Enabled / RST Controlled]`

{% hint style="info" %}
The names of these values might differ! Just use common sense! If you are completely unsure, feel free to make a ticket!
{% endhint %}

**Go to Boot tab:**

1. Set `CSM` -> `[ Disabled ]`
   * If you can't find CSM ensure UEFI is enabled.
2. Save & exit the BIOS, then return back to BIOS again!

#### Creating Array(s)

Now; Advanced -> Intel(R) RST navigate to `Create RAID Volume`

1. Set the `Name` -> Anything of your choice!
2. Set the `RAID Level` to `RAID0 (Stripe)`.
3. `Select disks` you want to raid with, you can't mix different disk types.
4. Click on `Create Volume` to create the array.

#### Installing windows

* Save & exit the BIOS and ensure the USB you set up is plugged into your pc.
* Change the language settings if needed.
* Press `next` in the setup.
* If the setup asks for product key, select `I don't have a product key`
* Select the operating system: `Windows 10 Pro`
* Accept the TOS and `press next`.
* Now at setup step `Where do you want to install Windows?` you select `Load driver`.
  * You will get a pop-up; select browse
  * Navigate to the USB stick.
  * Then select folder containing your drivers -> Press `Ok`.
  * Control + A; to select all the drivers, then select `next`.
* Select the disk you want to install Windows on and press next.
* Continue to install windows; then you're done!

#### How to check if my Raid worked after reinstalling windows?

1. **Open Task manager**
2. **Click Performance**
3. **Click on "Disk 0 (C:)"**
4. **Should say on top right "INTEL RAID"**

{% hint style="warning" %}
IF IT'S NOT SHOWING AS "INTEL RAID 0 VOLUME" — OPEN TICKET IN DISCORD SERVER discord.gg/DRr7VmPRkh
{% endhint %}
