# ditch-enrollment
# A guide on how to UNENROLL ALL CHROMEBOOKS ON DIFFERENT KERNVERS


> [!WARNING]
> I am not held responsible for ANY trouble you get in using this repo


> [!NOTE]
> REQUIRMENTS: A USB WITH 8GB+ STORAGE


# KERNVER 1-2: SH1MMER:
so first head over to: [CROS.DOWNLOAD](https://cros.download/shims) and download your Chromebook Board name you can find it by heading over to chrome://version.
then after you download your shim (corresponding to your boardname) head over to here: [Wax4Web](https://sh1mmer.me/builder). then it downloads a .bin file, named something like (injected-shim.bin) then you use [Chromebook Recovery Utility](https://chromewebstore.google.com/detail/chromebook-recovery-utili/pocpnlppkickgojjlmhdmidojbmbodfm?hl=en) to flash the injected-shim onto the USB drive. then you press, esc+refesh+power and then hit ctrl+d then press esc+refresh+power again and then plug in your USB drive and then once your in the sh1mmer payload select Unenroll!


# KERNVER 2: CRYPTOSMITE:
so head over to: https://github.com/FWNavy/CryptoSmite/blob/main/cryptosmite.md
and download the stateful.tar.xz and st.tar.xz files.
then use wax4web to get a injected-shim.bin file and then (im not gonna explain again, just do the steps from SH1MMER to flash on the usb and shit like that..) and yeah, you should be unenrolled now!


# KERNVER 3: OlyBmmer: so first get a RECOVERY IMAGE, NOT A RMA SHIM:  [CROS.DOWNLOAD](https://cros.download/recovery)
and download that, afer thats done head over to, the BadRecovery Web Builder: https://binbashbanana.github.io/badrecovery/ and then you'll get a .bin file (then flash the .bin file onto the usb via Chromebook Recovery Utility.) and yeah! you should be unenrolled now!
