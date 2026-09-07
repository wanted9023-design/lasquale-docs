# Secure Boot Bypass

### Follow these Steps

{% hint style="danger" %}
Before Bypassing Secure Boot:
**Run requirements installer.bat.**
{% endhint %}

1. Open LaSquale Loader & navigate to the spoofer tab.

2. Locate the EFI Spoof Button.

3. Then click Auto Create Partition.

{% hint style="info" %}
Wait until the message **"EFI Spoof Completed"** appears.
{% endhint %}

4. Configure BIOS Boot Options

{% hint style="info" %}
Enter Your BIOS Setup
{% endhint %}

5. Go to the Boot Options section.

{% hint style="success" %}
SET:
Boot Option #1 to the new partition created during spoofing (usually labelled something like 4 GPT).

SET:
Boot Option #2 to your regular Windows boot drive.
{% endhint %}

6. Secure Boot Settings — **Navigate to the Boot tab.**

{% hint style="success" %}
Set:
OS Type to Windows UEFI Mode.
Secure Boot Mode to Custom.
{% endhint %}

7. Key Management — **Go to Key Management.**
   * Click Clear Secure Boot Keys.
   * Then click Install Default Secure Boot Keys.

8. Append KEK Certificate — **Go to KEK Management and select Append Key**

   🔹 When prompted, click No to load from internal storage.
   🔹 Choose to load from external media.
   🔹 Locate the spoofed partition (typically labelled 4 GPT).
   🔹 Inside, find and select the .der file.
   🔹 Choose Public Key Certificate, then confirm with Yes.

9. Append DB Certificate

{% hint style="info" %}
Repeat the same process as in Step 8, but this time under DB Management.
{% endhint %}

---

{% hint style="info" %}
**Note: This process is important for ASUS users.** You would **ALWAYS** have to boot Windows from the Partition / USB. You cannot play Fortnite (or any other Game, that requires Secure Boot) without it. Sadly, there is no other way for this, other than buying a new motherboard.
{% endhint %}
