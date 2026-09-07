# Step 3: Configuring BIOS

### Intel CPU:

{% tabs %}
{% tab title="ASUS" %}
1. Virtualization:
   1. Advanced -> CPU Configuration -> `Intel (VMX) Virtualization Technology` set to `Disabled`.
2. VT-d:
   1. Advanced -> System Agent (SA) Configuration -> `VT-d` set to `Disabled`.
3. TPM:
   1. Advanced -> PCH-FW -> `TPM Device Solution` set to `Enable Discrete Firmware/TPM`.
   2. Advanced -> Trusted Computing -> `Security Device Support` set to `Disabled`.
4. Armoury Crate:
   1. Tool -> ASUS Armoury Crate -> `Download & Install ARMOURY CRATE app` set to `Disabled`.
5. Fast Boot:
   1. Boot -> `Boot Configuration` -> Fast Boot set to `Disabled`.
6. Secure Boot:
   1. Boot -> Secure Boot -> `OS Type` set to `Other OS`.
7. Wifi & Bluetooth
   1. Advanced -> Onboard Devices -> `CNVi Module` / `Wifi & BlueTooth` connectivity set to `Disabled`.
{% endtab %}

{% tab title="MSI" %}
1. Virtualization:
   1. OC -> CPU Features -> `Intel Virtualization Tech` set to `Disabled`.
2. VT-d:
   1. OC -> CPU Features -> `Intel VT-D Tech` set to `Disabled`.
3. TPM:
   1. Settings -> Security -> Trusted Computing -> `TPM Device Selection` set to `dTPM`.
   2. Settings -> Security -> Trusted Computing -> `Security Device Support` set to `Disabled`.
4. MSI Driver Utility Installer:
   1. Settings -> Advanced -> `MSI Driver Utility Installer` set to `Disabled`.
5. Fast Boot:
   1. Settings -> Boot -> `Fast Boot` set to `Disabled`.
6. Secure Boot:
   1. Settings -> Security -> Secure Boot -> `Secure Boot` set to `Disabled`.
7. Wifi & Bluetooth
   1. Settings -> Intergrated Peripherals -> `CNVi Module` / `Wifi & BlueTooth` connectivity set to `Disabled`.
{% endtab %}

{% tab title="GIGABYTE" %}
1. Virtualization:
   1. Tweaker -> Advanced CPU Configuration -> `Intel (VMX Virtualization Technology` set to `Disabled`.
2. VT-d:
   1. Settings -> Miscellaneous -> `VT-d` set to `Disabled`.
3. TPM:
   1. Settings -> Miscellaneous -> `Intel Platform Trust Technology (PTT)` set to `Disabled`.
   2. Settings -> Miscellaneous -> Trusted Computing -> `Security Device Support` set to `Disabled`.
4. Gigabyte Utilities Downloader Configuration:
   1. Settings -> IO Ports -> Gigabyte Utilities Downloader Configuration -> `Download & Install app` set to `Disabled`.
5. Fast Boot:
   1. Boot -> `Fast Boot` set to `Disabled`.
6. Secure Boot:
   1. Boot -> Secure Boot -> `Secure Boot Enable` set to `Disabled`.
7. Wifi & Bluetooth:
   1. [Follow this.](https://youtu.be/4mQBteWM9wE) - This is not required, but recommended.

{% hint style="warning" %}
On certain Gigabyte boards, normally ones particular to overclocking, it may differ in terms of finding where these settings are, in these cases, it may be under "M.I.T" or other pages, have a look around and if you need further support, make a ticket.
{% endhint %}
{% endtab %}

{% tab title="Other" %}
1. Virtualization
2. VT-D
3. TPM
4. Utility Installer
5. Fast Boot.
6. Secure Boot
7. Wifi & Bluetooth (WAN Radio On ASROCK)
{% endtab %}
{% endtabs %}

{% hint style="success" %}
Remember: On every motherboard it's different, have a look around, if you can't find the right ones or are confused, feel free to open a ticket.
{% endhint %}

### AMD CPU:

{% tabs %}
{% tab title="ASUS" %}
1. Virtualization:
   1. Advanced -> CPU Configuration -> `SVM Mode` set to `Disabled`.
2. AMD NX Mode:
   1. Advanced -> CPU Configuration -> `NX Mode` set to `Disabled`.
3. AMD IOMMU:
   1. Advanced -> AMD CBS -> `IOMMU` set to `Disabled`.
4. TPM:
   1. Advanced -> AMD fTPM -> AMD fTPM Switch set to `Disabled`.
   2. Advanced -> Trusted Computing -> `Security Device Support` set to `Disabled`.
5. Armoury Crate:
   1. Tool -> ASUS Armoury Crate -> `Download & Install ARMOURY CRATE app` set to `Disabled`.
6. Fast Boot:
   1. Boot -> `Boot Configuration` -> Fast Boot set to `Disabled`.
7. Secure Boot:
   1. Boot -> Secure Boot -> `OS Type` set to `Other OS`.
8. Wifi & Bluetooth
   1. Advanced -> Onboard Devices -> `Wifi & BlueTooth` connectivity set to `Disabled`.
{% endtab %}

{% tab title="MSI" %}
1. Virtualization:
   1. OC -> Advanced CPU Configuration -> `SVM Mode` set to `Disabled`.
2. NX Mode:
   1. OC -> Advanced CPU Configuration -> `NX Mode` set to `Disabled`.
3. IOMMU:
   1. OC -> Advanced CPU Configuration -> AMD CBS -> `IOMMU` set to `Disabled`.
4. TPM:
   1. Settings -> Security -> Trusted Computing -> `AMD fTPM Switch` set to `AMD CPU fTPM Disabled`.
   2. Settings -> Security -> Trusted Computing -> `Security Device Support` set to `Disabled`.
5. MSI Driver Utility Installer:
   1. Settings -> Advanced -> `MSI Driver Utility Installer` set to `Disabled`.
6. Fast Boot:
   1. Settings -> Boot -> `Fast Boot` set to `Disabled`.
7. Secure Boot:
   1. Settings -> Security -> Secure Boot -> `Secure Boot` set to `Disabled`.
8. Wifi & Bluetooth
   1. Settings -> Intergrated Peripherals -> `Wifi & BlueTooth` connectivity set to `Disabled`.
{% endtab %}

{% tab title="GIGABYTE" %}
1. Virtualization:
   1. Tweaker -> Advanced CPU Configuration -> `SVM Mode` set to `Disabled`.
2. AMD NX Mode:
   1. Tweaker -> CPU Configuration -> `NX Mode` set to `Disabled`.
3. AMD IOMMU:
   1. Settings -> Miscellaneous -> `IOMMU` set to `Disabled`.
4. TPM:
   1. Settings -> Miscellaneous -> `Trusted Platform Module` set to `Disabled`.
   2. Settings -> Miscellaneous -> Trusted Computing -> `Security Device Support` set to `Disabled`.
5. Gigabyte Utilities Downloader Configuration:
   1. Settings -> IO Ports -> Gigabyte Utilities Downloader Configuration -> `Gigabyte Utilities Downloader` set to `Disabled`.
6. Fast Boot:
   1. Boot -> `Fast Boot` set to `Disabled`.
7. Secure Boot:
   1. Boot -> Secure Boot -> `Secure Boot Enable` set to `Disabled`.
8. Wifi & Bluetooth:
   1. [Follow this.](https://youtu.be/4mQBteWM9wE) - This is not required, but recommended.

{% hint style="warning" %}
On certain Gigabyte boards, normally ones particular to older overclocking, it may differ in terms of finding where these settings are, in these cases, it may be under "M.I.T" or other pages, have a look around and if you need further support, make a ticket.
{% endhint %}
{% endtab %}

{% tab title="OTHER" %}
1. SVM Mode
2. IOMMU
3. TPM
4. Utility Installer
5. Fast Boot.
6. Secure Boot
7. Wifi & Bluetooth (WAN Radio On ASROCK)
{% endtab %}
{% endtabs %}

{% hint style="success" %}
Remember: On every motherboard it's different, have a look around, if you can't find the right ones or are confused, feel free to open a ticket.
{% endhint %}
