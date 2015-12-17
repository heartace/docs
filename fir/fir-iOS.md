# Using fir to install iOS app

This mansual will describe how to install internal build of iOS app on your device.

## What is fir?

[fir](http://fir.im/) is a web service for in-house app distribution. We'll use it to download and install the testing build internally.

## What is UDID?

`UDID` is the unique identifier of an iPhone or iPad. To install the app from fir on your device, you havel

## Install profile and get UDID

Open [fir.im](http://fir.im/) in `Safari` app on your `iPhone`.

Tap `Get UDID` button and it will switch to system settings page.

Tap `Install` button on upper-right corner and accept.

It will switch back to `Safari` and if everything works well you'll see:

## Send UDID

Tap `Send UDID` button and send it to the developer team.

## Download and install the app

When the app is uploaded to fir by developers, a short URL like `http://fir.im/ab12` will be generated, and be the permanant link of the app. 

Open that link in `Safari`, tap `Download` button and then `OK`. The app will start to be downloaded and installed on your iPhone, just as it is from App Store.

Everytime the app updated, you could just open the same link and perform the actions as before. The app on your device will be updated.