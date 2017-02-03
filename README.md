# LibreSignal *forever*

Just a fork of the last LibreSignal build that was available via the experimental Eutopia.cz F-Droid repository.

This adds [a patch](https://github.com/gehaxelt/LibreSignal/commit/c9e4d37f28cff31c24955168a441a6d169d81f0a) by [@gehaxelt](https://github.com/gehaxelt) that removes the expiry message preventing users from sending messages.

Also, `org.libresignal` was changed back to `org.thoughtcrime.securesms` for compatibility because that's what the F-Droid build did.

## Building

> **This is not (and will not be) available for download anywhere!**

You will have to build it yourself. See BUILDING.md.  
Using `./gradlew -x lint -x javadoc build` worked for me.

## Support / Bug Fixes / Feature Requests / Updates …

no.

## Signal

Since LibreSignal has been abandoned but has a 90 day killswitch, this is only provided as a temporary transitional "emergency" solution for people without GApps to use until Signals [works without it](https://github.com/LibreSignal/LibreSignal/issues/43).

Note: It's only called *forever* because it doesn't expire ¯\\\_(ツ)\_/¯ 