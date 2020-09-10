Download the One-tap checkra1n for Android app (checkra1n TWRP): https://downthecrop.xyz/blog/checkra1n-android-twrp-app/


[![How to run checkra1n on Android to jailbreak iOS](https://downthecrop.xyz/blog/wp-content/uploads/2020/03/checkra1n-android-1-1024x576.png "How to run checkra1n on Android to jailbreak iOS – [Watch my video guide here!](https://www.youtube.com/watch?v=tc0GqDueUIE)")](https://www.youtube.com/watch?v=tc0GqDueUIE)
How to run checkra1n on Android to jailbreak iOS – [Watch my video guide here!](https://www.youtube.com/watch?v=tc0GqDueUIE)

X-Posted from https://downthecrop.xyz/blog/jailbreak-ios-device-with-android-phone-checkra1n-for-android-tutorial/

# Jailbreak iOS device with Android Phone – checkra1n for Android Tutorial
Run checkra1n on Android to Jailbreak iOS device

How to run checkra1n on Android to jailbreak iOS – Watch my video guide here!
Did you know you can use an Android Phone to jailbreak iOS using checkra1n? Here’s the step by step guide and tutorial to explain how to run checkra1n on Android.

- Rooted Android device
- USB-C to USB-A Adapter
- Lightning cable
- TWRP Custom Recovery

When you have gathered the supplies navigate to the official checkra1n website and download the lastest arm64 Linux binary of checkra1n

https://checkra.in/

Note the location you downloaded the file to. You will need to know the absolute path the file is located so you can execute it from a terminal command line.

Once you have the file downloaded boot your Android phone into Custom Recovery. Running the tool from Custom Recovery instead of directly inside Android you don’t need to worry about a conflict between different processes fighting over the USB controller. I wasn’t able to run checkra1n from a fully booted Android 10 but I was able to run it from Custom Recovery! Your luck may vary but Custom Recovery is the most reliable option.

Open a Terminal in Custom Recovery (TWRP 3.3.1-17 was used in my video) and change directory to where you saved checkra1n

`cd /sdcard/Download`

Next we need to add the execute flag to the binary so it can be run as a program

`chmod +x checkra1n`

Finally we can run checkra1n from Android

`./checkra1n -c -v`

Connect your iOS device using your USB-C to USB-A adapter and your Lightning cable.

Now we need to manually enter DFU mode on our iOS device. This is done differently on different devices so if you are unsure just look up “How to put iPhone X into DFU mode” replacing iPhone X with your model and you should find some button combinations to enter DFU.

If you have successfully put your iOS device into DFU and it is connected to your Android Phone running checkra1n the program should recognize the DFU mode USB device and run the exploit!

For a complete step by step guide of using the new checkra1n for Android you can follow my [YouTube guide here](https://www.youtube.com/watch?v=tc0GqDueUIE)
