## KIFSpecs

Square hasn't released an official CocoaPods spec for
[KIF](https://github.com/square/KIF), which means the
spec in the master spec repo is fast-becoming
obsolete. Indeed, it doesn't build using Xcode 4.5.

KIFSpecs is an unofficial spec repo for KIF users. I will
update the spec as often as necessary.

Please file an issue if you would like an update to
the latest SHA1 on https://github.com/square/KIF master.


### Installation

To add this repo to your CocoaPods spec repositories, use
the following command:

`$ pod repo add KIFSpecs git@github.com:modocache/KIFSpecs.git`

Then add the following to your Podfile:

`pod 'KIF', '~> 0.0.2'`
