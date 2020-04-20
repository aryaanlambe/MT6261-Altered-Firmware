# MT6261-Altered-Firmware
Altered firmware files for specific MT6261-based Chinese smartwatches (non-android)

Everything written here is based experiences I had while working with the MT6261 platform.

**WARNING**: This firmware works for the following smartwatches and their clones. If your smartwatch does not look like anything in the below picture, this repository IS NOT for you. Since you've made it this far, I'm assuming you're atleast mildly computer savvy and/or have dealt with the likes of custom roms, UART settings and Serial BAUD-rates, albeit probably on other platforms. Nevertheless, I strongly recommend you go through this document in its entirety.

This smartwatch goes under many names: JHCY V9, Beseneur V9, Fu&y Bill V9, Dicekoo V9 to name a few.

![V9-Bluetooth-Smart-Watch-Sync-Notifier-Support-Sim-Card-Sport-Smartwatch-For-apple-iphone-Android-Phone](https://user-images.githubusercontent.com/52194584/79750910-02eda480-8312-11ea-8b4e-93fa556efad2.jpg)

### Firmware Info:
- These may be different depending on the vendor for your watch (mine was JHCY).

```
[VERSION] K12-V907789HSD-DC3A01-BDYD-RD-V06.99-20180404-ZX
[BRANCH] 11C-UME0X61D_BT_11AC
[SERIAL#] SN001234567
[MRE VERSION] 3100
[HAL_VERNO] n/a
[BB CHIP] MT6261
[DSP PATCH] 1.0
[MS BOARD] K91
[OS] RTOS Nucleus
```

### Service Codes:
- These codes can be entered in the Dialler app of the smartwatch, no simcard is neccessary for these codes and they should trigger instantaneously once they're entered.

```
		*# 8375 # - Version summary.
		*# 3646633 # - Engineer mode. 
		*# 66 *# - Factory diagnostics mode.	
```
## FAQ:
- What is the aim of this repo? **The aim of this repo is to provide a guide as to how to alter watchfaces, sounds, images that the watch's proprietary OS would otherwise not let you change along with how to utilize the most out of the, rather dismal, array of features this particular smartwatch has.**
- How can I change the OS entirely? Can I flash something like AsteroidOS? **No, you can't. The watch is too weak to run Asteroid OS.**
- Can I change the menu or remove features I don't use? **Unfortunately, that cannot be done, since the OS the watch is using is MediaTek proprietary and I don't have access to their sources.**
- Could you add in this watchface for me? **Sadly I can't due to time constraints, however, if you're able to follow this guide word for word, you should be able to add it in yourself.**
- I intend on buying this smartwatch & happened to chance upon this repo. Would you recommend this smartwatch? **I would strongly encourage you stay away from any smartwatch that is based on RTOS Nucleus and instead go for an android-smartwatch, It's not that it's easier to tinker with android-based smartwatches, it's just that the platform is much more open and there's a much larger community pool and know-how around it (and android-based smartwatches usually tout features that actually work as compared to their RTOS Nucleus counterparts.).**