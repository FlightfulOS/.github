# What is this for?
This organization holds a customized version of [GrapheneOS](https://grapheneos.org).

# Projects
## GrapheneOS
[GrapheneOS](https://grapheneos.org) is a "privacy and security focused mobile OS" based on Android. Among many, many other features, it [sandboxes Google Play services](https://grapheneos.org/usage#sandboxed-google-play), preventing the overreaching that Google relies on to collect data.

## microG
[microG](https://microg.org) is "a free-as-in-freedom re-implementation of Google’s proprietary Android user space apps and libraries". Unfortunately, microG relies on signature spoofing. (Signature spoofing is basically when an app lies to other apps about who signed it. In this case, microG pretends to be Google.) Additionally, it needs to be run as a privileged system app to use every feature - although it's not necessary!

# FAQ
## Is your version more secure than stock GrapheneOS?
*No.* [microG](https://microg.org) relies on signature spoofing. While I try to mitigate this concern by limiting it to their signature and package names, it is inherently bypassing a security feature.

GrapheneOS talked about microG [on Twitter](https://twitter.com/GrapheneOS/status/1437380576055541761). Some of these points have been responded to [in an interview](https://youtube.com/watch?v=8sfnzd_mTOQ).

## Where's the source code?
* Upstream GrapheneOS source code is available at [https://github.com/GrapheneOS](https://github.com/GrapheneOS).
* Upstream microG source code is avalable at [https://github.com/microG](https://github.com/microG).
* A very, very small amount of CalyxOS code is used - which is available at [https://github.com/CalyxOS/platform_frameworks_base](https://github.com/CalyxOS/platform_frameworks_base).

## How can I get this?
Build it yourself. *I'm not responsible*, as-is basis, no warranties (even implied), no guarantee, yada yada. **I will not help you. I make this for myself and myself only.**
