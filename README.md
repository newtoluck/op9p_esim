# OnePlus 9 Pro eSIM Module

Magisk/KernelSU/APatch module to enable Google's proprietary internal manager (from Pixel) of eSIM profiles when an removable eUICC (eSIM card) is installed.

## Compatibility
Tested with OnePlus 9 Pro LE2120 (CN) with Nameless AOSP 14 and KernelSU v0.9.5. Theoritically it should work with any OnePlus 9 Pro variant running custom AOSP based ROMs. Oxygen OS are not guaranteed to work as it may have different implementation of eSIM management (LPA).

## Usage
Download the latest [release](https://gitlab.com/xymeng16/op9p_esim/-/releases) and install it via the root manager you are using. Once installed, reboot the device and you should see the `Add SIM` option in `Setting->Network & Internet->SIMs`

## Disclaimer
This module is provided as is and I am not responsible for any damage caused by using this module. Use at your own risk.

> Some precompiled binaries are borrowed from OnePlus 11's firmware. I do not own any rights to these binaries.
>
> system/system_ext/priv-app/OplusEuicc/OplusEuicc.apk is partially borrewed from LineageOS and compiled&signed by myself. It provides the correct SIM slot mapping of OnePlus 9 Pro to the SIM Manager. If you are worried about the security, you may compile it by yourself. The source code is available at https://gitlab.com/xymeng16/opluseuicc. Apache-2.0 license is applied.
>
> system/system_ext/priv-app/EuiccGoogle/EuiccGoogle.apk is actually https://play.google.com/store/apps/details?id=com.google.android.euicc. I downloaded it from https://www.apkmirror.com/apk/google-inc/esim-manager/esim-manager-d-2-1-635558248-google-release/. I do not own any rights to this APK and it's highly recommended to download it by yourself and check the signature before using it.