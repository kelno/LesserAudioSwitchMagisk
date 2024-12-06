This is a Magisk module installing a modded 2.7.2 Lesser AudioSwitch and enabling android.permission.MODIFY_AUDIO_ROUTING for it. Nothing else is done here.  

> [!WARNING]
> I'm not the author of the modded apk and cannot vouch for it's reliability or trustworthiness.  

# Lesser AudioSwitch Magisk module
Lesser Audio Switch, Magisk Module, for rooted Android 11+

## Requirement
- Root (for installing)  
- Magisk v20.4+

## Tested
Works on my fairphone 3 with LineageOS 21 (Android 14), with Magisk 28003.

## Known issues
- [Forcing the bluetooth microphone doesn't work (on some phones?) (link to issue)](https://github.com/kelno/LesserAudioSwitchMagisk/issues/1)
  
Maybe we can mod the app further to fix it, help is welcome! I have no experience in Android development.
  
## How to use
Make sure all versions of regular Lesser AudioSwitch are uninstalled before installing this module. (not 100% sure it's needed but author of APK specifies this)  
Download from [Release page](https://github.com/kelno/LesserAudioSwitchMagisk) and install it with Magisk Modules Manager.  
  
## Modded APK (notes by zelo)  
- updated to app release 2.7.2  
- unlocked all premium features  
- fixed bugs that would not allow audio route switching  
- fixed crashes  
- removed all garbage, analytics, ads, google shit  
- shrunk package size  
- updated package signature  

## Credits
Original app by Roughy AKA Mathias Nordskog.  
@zelodev on telegram for the modded APK.  
Originally forked from https://github.com/michioxd/LesserAudioSwitchAndroid11 and everything is changed now but this helped!  
