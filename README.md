## Mobitile Client Application Technical Notes

##### Patform
* [Adobe AIR] 
* [Stage3D] - allows access to GPU hardware acceleration;
* [Starling] - 2D Engine built on Stage3D, simplifies work with Stage3D;

##### UI
* [Feathers] - component framework built on [Starling];
* [skein-components] - for building layout;
* [skein-validation] - for form validation;
* [skein-binding] - for data binding;
* [skein-popups] - for work with popoups.

##### Application Architecture
* [Cairngorm Guidelines] - gudelines for building applictions;
* [Parsley] - microarchitecure framework (adopted for Starling);
* [cairngorm-navigation] - for application navigation;

##### Client-Server Communication
* [skein-rest] - for RESTfull services, with DefaultRestClient based on standard [URLLoader]
* [socket.io-client.as3] - socket.io for Messenger built on Node.js server through [socket.io] v 1.0 protocol.

##### P2P Communication
* [RTMFP] - for audio/video data, protcol [specification](http://tools.ietf.org/html/draft-thornburgh-rtmfp-flash-04). [article1](http://www.adobe.com/devnet/flashplayer/articles/rtmfp_cirrus_app.html), [article2](http://www.adobe.com/devnet/adobe-media-server/articles/p2p_rtmfp_groups.html)

##### Native Extensions
* [com.github.rozd.ane.Contacts] - for access to Address Book;
* [com.github.rozd.ane.DeviceInfo] - provides additional data about Device;
* [pl.mateuszmackowiak.nativeANE.NativeDialogs] - for working with native dialogs;
* [com.freshplanet.AirPushNotification] - for Push Notification (**NOT USED YET**);
* [com.thejustinwalsh.TestFlight] - for integration with TestFlight (**NOT USED YET**);
* [com.sampleNativeExtensions.Maps] - access to native maps application (**NOT USED YET**).

[Adobe AIR]:http://labs.adobe.com/downloads/air.html
[RTMFP]:http://labs.adobe.com/technologies/cirrus/
[URLLoader]:http://help.adobe.com/en_US/FlashPlatform/reference/actionscript/3/flash/net/URLLoader.html
[Starling]:http://gamua.com/starling/
[Stage3D]:http://www.adobe.com/devnet/flashplayer/stage3d.html
[Feathers]:http://feathersui.com
[Parsley]:https://github.com/rozd-spicefactory/parsley-starling
[cairngorm Guidelines]:http://sourceforge.net/adobe/cairngorm/wiki/CairngormGuidelines/
[socket.io]:http://socket.io

[skein]:https://github.com/skeinlib/skein/
[skein-components]:https://github.com/skeinlib/skein/tree/master/skein-components
[skein-binding]:https://github.com/skeinlib/skein/tree/master/skein-binding
[skein-validation]:https://github.com/skeinlib/skein/tree/master/skein-validation
[skein-popups]:https://github.com/skeinlib/skein/tree/master/skein-popups
[skein-rest]:https://github.com/skeinlib/skein/tree/master/skein-rest
[cairngorm-navigation]:https://github.com/rozd-cairngorm/cairngorm-navigation
[socket.io-client.as3]:https://github.com/skeinlib/socket.io-client.as3

[com.github.rozd.ane.Contacts]:https://github.com/rozd/contacts
[com.github.rozd.ane.DeviceInfo]:https://github.com/rozd/deviceinfo
[pl.mateuszmackowiak.nativeANE.NativeDialogs]:https://github.com/mateuszmackowiak/NativeDialogs
[com.freshplanet.AirPushNotification]:https://github.com/freshplanet/ANE-Push-Notification
[com.thejustinwalsh.TestFlight]:https://github.com/thejustinwalsh/TestFlightANE
[com.sampleNativeExtensions.Maps]:https://code.google.com/p/air-maps-ane/