# ditch-enrollment
# A guide on how to UNENROLL ALL CHROMEBOOKS ON DIFFERENT KERNVERS


> [!WARNING]
> I am not held responsible for ANY trouble you get in using this repo


> [!NOTE]
> REQUIRMENTS: A USB WITH 8GB+ STORAGE, ANOTHER COMPUTER


# KERNVER 1-2: SH1MMER:
so first head over to: [CROS.DOWNLOAD](https://cros.download/shims) and download your Chromebook Board name you can find it by heading over to chrome://version.
then after you download your shim (corresponding to your boardname) head over to here: [Wax4Web](https://sh1mmer.me/builder). then it downloads a .bin file, named something like (injected-shim.bin) then you use [Chromebook Recovery Utility](https://chromewebstore.google.com/detail/chromebook-recovery-utili/pocpnlppkickgojjlmhdmidojbmbodfm?hl=en) to flash the injected-shim onto the USB drive. then you press, esc+refesh+power and then hit ctrl+d then press esc+refresh+power again and then plug in your USB drive and then once your in the sh1mmer payload select Unenroll!


# KERNVER 2: CRYPTOSMITE:
so head over to: https://github.com/FWNavy/CryptoSmite/blob/main/cryptosmite.md
and download the stateful.tar.xz and st.tar.xz files.
then use wax4web to get a injected-shim.bin file and then (im not gonna explain again, just do the steps from SH1MMER to flash on the usb and shit like that..) and yeah, you should be unenrolled now!


# KERNVER 3: OlyBmmer: so first get a RECOVERY IMAGE, NOT AN RMA SHIM:  [CROS.DOWNLOAD](https://cros.download/recovery)
and download that, afer thats done head over to, the BadRecovery Web Builder: https://binbashbanana.github.io/badrecovery/ and then you'll get a .bin file (then flash the .bin file onto the usb via Chromebook Recovery Utility.) and yeah! you should be unenrolled now!


# KERNVER 4: ICARUS: so i think from my understanding, icarus is a bit different. You gotta unenroll via usb via shim then you spoof with an ip.
So head over to here: https://dl.snerill.org/icarus to get your RMA shim (Corresponding to your Boardname)
So after you unenroll go to WiFi-Settings, then Change the Proxy Type to Manual. And to Host your own proxy here: https://www.youtube.com/watch?v=trqwRNPcVV4
AND AFTER HOSTING ICARUS ON YOUR OWN COMPUTER, MAKE SURE TO THAT After unenrolling change back to direct internet connection in proxy settings

# KERNVER 5: Br0ker:
i dont know shit abt kernver 6 unenrollment tho but im sure the quicksilver and badsilver shims are on the: https://dl.snerill.org website.
alr so get Br0ker shim from here: https://github.com/ading2210/sh1mmer/releases/tag/2025.9.19 and btw IGNORE THE ASSETS SECTION. SO first download the RMA shim corresponding to your Boardname and then flash with chromebook recovery utility, then press the keys (esc+refresh+power) then plug in Your USB then just wait, and then yeah your unenrolled after that! (hope you enjoyed my guide!).



## What Kernver and ChromeOS version do I have?
[What Kernver and ChromeOS version do I have?](#what-kernver-and-chromeos-version-do-i-have)

# *(You can find your Kernver version by pressing, esc+refresh+power and pressing Tab, Its the line that reads: tpm_kernver=0x00010004, if it reads that, Then Your Kernver is 4! and for your chromeos version you just have to press, Alt+V on then sign-in screen and you'll see your version.)*


# KERNVER 6: QUICKSILVER:
# so first head over to https://dl.snerill.org/QuickSilver then download the shim, corresponding to your boardname, then unzip the file and flash the .bin file onto your USB and then boot into quicksilver by pressing, esc+refresh+power then plug in/insert your usb and there you go, goodjob!



# KEYROLLED: KERNVER 6: 
# there is two methods, both work on kernver 6 keyrolled chromebooks: Badsilver or BadSH1mmer, so first head over to https://dl.snerill.org and pick your method, then download the shim corresponding to your boardname, then (flash onto usb via chromebook recovery utility, AFTER YOU UNZIP AND THE HAVE THE .bin FILE, then press esc+refresh+power then plug in your usb drive and then yeah you should be unenrolled now, good job!


# Dededeicarus
> [!WARNING]
> DEDEDEICARUS IS ONLY FOR KEYROLLED DEDEDE CHROMEBOOKS IF YOUR CHROMEBOOK IS NOT A DEDEDE BOARD, THEN DEDEDEICARUS IS NOT FOR YOU
# INSTRUCTIONS ARE ON HERE: https://github.com/crosbreaker/dededeicarus



# What even is Keyrolling?


# So Keyrolling is where newer boardnames, (Like Nissa) are like LOCKED DOWN so you can't just like unenroll without like Newer Methods (Like BadSH1mmer) and stuff like that



# And What should I do After Unenrolling?



# ANSWER: I WOULD USE MURKMOD AFTER UNENROLLING SUCESFULLY BECAUSE MURKMOD SPOOFS THE FACT THAT THE CHROMEBOOK GOT UNENROLLED, BECAUSE IF YOU DON'T USE MURKMOD AFTER UNENROLLING YOUR SYSADMIN WILL PROBABLY FIGURE OUT THAT THE CHROMEBOOK IS UNENROLLED FROM THE GOOGLE ADMIN CONSOLE
