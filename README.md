# WWDC 2020 Session Notes

<a href="https://twitter.com/blackjacxxx"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/blackjacxxx?label=%40Blackjacxxx"/></a>
<a href="https://www.paypal.me/STHEROLD"><img alt="Donate" src="https://img.shields.io/badge/Donate-PayPal-blue.svg"/></a>

## Thank You 🎉

Last years [WWDC Session Notes](https://github.com/Blackjacx/WWDC/tree/2019) was so successful that I decided to continue this form of WWDC session summary. I would like to take the moment to thank all of you for contribution, feedback, support and reading my session notes 🙏

## Intro

Usually it is much faster to read through some bullet points instead of watching a 50 min session video. Then if you find something interesting you can still watch it.

Sessions that are exceptionally mentionable are highlighted using a ★.

> This is work in progress since it is a lot of effort to watch all the videos by myself. So either please be patient or just [open up an issue](https://github.com/Blackjacx/WWDC/issues/new) to make a suggestion which session notes you like to see next :)

## Contribution

Feel free to submit a `PR` if I got something wrong or you have a suggestion for improvement. Please also have a look in [CONTRIBUTING.md](CONTRIBUTING.md) if you want to contribute.

Thanks so much to EVERYBODY who contributed and improved the overall quality of the notes and those who added complete notes to the list:

## Mentions

This repo has already been mentioned many times on Twitter and apart from this also in the following places:

- [iOS Dev Weekly Issue 409](https://iosdevweekly.com/issues/409)
- [iOS Goodies Issue 287](https://ios-goodies.com/post/185729205551/week-287)
- [Swift Developments Issue 189](https://andybargh.com/swiftdevelopments-189/)
- [WWDCNotes](https://www.wwdcnotes.com/)

## Interesting WWDC-Related Links

- [Apple Developer Documentation](https://developer.apple.com/documentation) by [@Apple](https://twitter.com/apple)
- [Xcode Release Notes](https://developer.apple.com/documentation/xcode_release_notes/)
- [iOS & iPadOS Release Notes](https://developer.apple.com/documentation/ios_ipados_release_notes)

## Table of Contents

1. [Keynote ★](#keynote-)
1. [Platform State of the Union ★](#platform-state-of-the-union-)
1. [Explore ARKit 4](#explore-arkit-4)

## Keynote ★

https://developer.apple.com/wwdc20/101/

- **App Library**
  - Automatically created at the end of your app pages on the Home Screen
  - Makes it easier than ever to get to your apps
- **Widgets on Home Screen**
  - Richer UI - more possibilities
  - Different sizes to choose one that best fits your needs
  - Droppable on the home screen
  - Widget gallery to explore all widgets
  - **SmartStack** as intelligent assistent which enables you to scroll through your widgets
- **Picture in Picture** on iPhone
  - Swipe to the side, out of the screen, and audio keeps playing
  - Video keeps playing when switching apps
- **Siri**
  - Got smarter and has a new interface which doesn't block your UI anymore
  - Can now send audio messages using the messages app - completely hands free
- **Translate** as new app of offline conversation translate
  - Conversation mode when switching to landscape mode in the app
- **Messages**
  - Pinning messages to the top of the screen
  - Memoji gets hundrets of new options to customize your avatar, including masts, fist-pumps and more
  - Group conversations got some ❤️ by adding inline replies and most-active member widget
- **Maps**
  - More countries like UK, Ireland and Canada
  - It gets easier to find places you love and how you get there in an ecological way
  - Maps offers **Guides** that help you discover great new places
  - Brand new **cycling** option to reduce your carbon footprint
  - **EV-Routing** option to optimize your route for electric cars - e.g. by selecting routes with charging station on your way
- **CarPlay**
  - Add custom wallpapers
  - Car Key API - first supported by BMW - enable open/close/start your car
- **App Clips** as small, fast parts of an app, designed for speed
  - a way to discover what the App Store has to offer
  - launchable from the web, by NFC tags, QR codes or the brand new Apple designed tags
  - need to be less thatn 10 MB
  - Use Sign in with Apple to provide the most seamless app experience
  - Option to downlod the full app
- **iPadOS**
  - Photos app gets an all new side bar - new way to navigate and organize your photos
  - Incoming calls become unobstrusive using notification style UI (available for all apps: Whatsapp, Skype, ...) • available for iOS too
  - New searching experience
- **Apple Pencil**
  - **Scribble** lets you hand-write in any text field. iOS converts your writing then to text
  - **Smart Selection** lets you select single words / characters you've written using your pencil using iOS text recognition features
  - DataDetectors are used to automatically detect e.g. phone numbers, email addreses
- **AirPods**
  - are now able to automatically switch to new incoming audio sources
  - **Spacial Audio** for AirPods Pro (AirPods Motion API) to emulate movie theatre experience • use AirPods gyroscope to sync the sound to your head position/orientation
- **watchOS 7**
  - Configure your own watch faces styled by your current living style
  - Watch faces can now be shared on Websites or via the usual sharing features of watchOS
  - Workout app adds dance, cooldown, functional training and more workouts plus it is renamed to **Firness**
  - **Sleep Tracking** is a new app that helps you to get to bed at time using `Wind Down` which dims all distractions (also available in iPhone)
  - **Handwashing detection** to make sure you wash as long as you're supposed to
- **Privacy Improvements**
  - **Location** only share rouch location
  - **Camera** ...
  - **Tracking Control** require apps to ask befoe tracking
  - **App Privacy** makes data tracked by developers visible to the users before they download the app
- **Home**
  - Alliance among different manufacturers to make smart home devices even better
  - **Adaptive lighting** to auto-adjust color temperature throughot the day
  - **Cameras** get activity zones, richer notifications
  - **Face recognition** extends to Home Pod
  - **Camera** content can be displayed on TV via your Apple TV
  - **Apple TV**
    - Picture in Picture
    - Better Airplay in full 4K 
    - Apple TV+ already on over 1 billion devices
    - **Foundation** as newest production only available on Apple TV+
- **macOS Big Sur**
  - use of a lot of translucency
  - Design refresh for all system apps
  - New side and compact, space efficient toolbars
  - Control center now on the mac
  - **Notification Center**
    - Notification grouping
    - iOS widgets also available on the mac
  - **Messages** with new search, photo picker, messages effects, pin conversations, inline replies and more
  - **Maps** with indoor-maps, favorites, ETA from friends and all of it implemented using Catalyst
  - **Safari** with 50% faster page loading, Privacy Report via toolbar button, Web Extensions API, built-in translation
- **Mac**
  - Processor-transition to **Apple Silicon** - Apple's own processor line - bye bye Intel 👋
  - **Universal 2** is the new universal binary type that contains binaries compiled for both architectures
  - **Rosetta 2** lets existing app run on new architectures from day one by making them compatible at installation time 
    - Supports iPhone and iPad apps **directly**

## Platform State of the Union ★

https://developer.apple.com/wwdc20/102/

- Some new features: **AirPods Motion API**, **SwiftPM resources**, **New Catalyst Controls**, **ARKit 4**, **Widgets in SwiftUI**, **Depth API**, **TestFlight 100 Testers**, **SwiftUI Lifecycle**, **Catalyst Native Screen Resolution**, **Complications in SwiftUI**, **Xcode StoreKit Testing**, **HomePod Music Services**, **App Clips**, **New SwiftUI Controls**, **Xcode Tabs**, ...
- Users can make your app the default app used for email and set a default web browser
- Developers can bring existing webbroser extensions to Safari using a new command line tool
- **FindMy** can now leverage **all** iPhones out there to locate your devices, even if they are not connected to the internet ([applicable to all kinds of objects](developer.apple.com/find-my))
- Mac transition to **Apple Silicon** - Apple's own processor line - brings more security, better performance, longer battery life and amazing graphics
  - **Advantages**
    - Cached cloud content can be kept up to date for days, even if your mac goes to sleep
    - Higher quality, hardware-supported 4:4:4 encoder for e.g. better image quality when connecting your Mac via SideCar
    - Best-In-Class platform security
  - Apple provides a Developer Transition Kit
    - Mac mini enclosure + A12Z SoC
    - 16GB memory, 512GB SSD
    - macOS Big Sur Developer Beta + Xcode
  - First Macs will appear by end of the year
- **Universal 2** create universal apps that run on both Apple Silicon and older architectures
- Porting to Apple Silicon takes only a few days, even for grown projects. As a result, all Apple system apps are already converted in macOS Big Sur
- **Rosetta 2** lets existing app run on new architectures from day one by making them compatible at installation time 
  - Supports iPhone and iPad apps **directly**
- iOS/iPad Apps native ly on Mac
  - Apps will run natively on the Mac
  - Apps will automatically support features like resizing, Dark Mode, scrolling, multi-window, native share sheets, ...
  - Apple plans to make iOS/iPadOS apps available on the App Store for macs running with Apple Silicon
- **macOS Big Sur - macOS 11**
  - Rounded dock 🎉
  - Control center for mac
  - New translucent look for notification center
  - Refined layout for menus of the menu bar
  - New sheet presentation - parent window is dimmed
  - Completely re-designed toolbars with extending search fields and images provided by SF-Symbols
  - App-specific accent color
  - **macOS Catalyst**
    - macOS-specific implementation of iOS API's
    - native reolution support
    - Messages re-written in Catalyst
    - SwiftPlaygrounds will support multiple windows
- **iPadOS**
  - New sidebars can now expand from two-column layout to three-column layout - even available in portait mode
  - Recommended to use side bars instead of tab bars
  - New inline emoji picker - also for custom apps
  - New color picker UI - easily to adopt
  - New Depth API's gives you access to precise distance info captured by the lidar scanner on iPad
  - Dramatic improvement of people inclusion and motion detection - objects can be placed in front or behind real objects in the world
  - **Apple Pencil**
    - New **handwriting** improvements will work in your apps without any additional work
    - Hand-writing for any UITextField
    - Automatic support for **Scribble** which converts any hand-written text to typed text
    - Stroke API gives acces to the strokes as the user draws
    - **Smart Selection** lets you select single words / characters you've written using your pencil and iOS text recognition features
  - **iOS 14**
    - **Widgets**
      - New widgets take UX to a whole new level
      - Users can move them to the home screen
      - Widgets are packed as SwiftUI archives which are optimized for performance
      - Are rendered by the system at the right time, the user needs them
      - Can be smartly stacked to consume less space and let the user flip through them
      - Stack automatically moves the right widget to the op at just the right time
      - Configurable in the Widget Gallery
    - **App Clips**
      - Small part of the app which is light/fast and easily to discover
      - Can use Apple Pay and Sign in With Apple to provide a seamless UX
      - Easily discoverable in a variety of ways, like other apps  or places in the real world via new Apple-designed (QR like) codes which are basically NFC tags
      - Introduce users to what your app offers
    - **Misc. New Features**
      - Cycling directions, Guides and EV routing in Maps
      - Translate app
      - Messages inline replies
      - Car keys
      - App Library
      - On device dictation
  - **watchOS 7**
    - Xcode is now able to preview watchOS complications
    - SwiftUI complications
    - **Watch-face sharing** via default sharing capabilities, e.g Messages
  - **Xcode 12**
    - Cleaner, more expressive UI
    - Navigators realized using the new Side Bar
    - Any kind of content is now openable in document tab
    - Navigate through nested calls in compiler failure messages
    - StoreKit tests lets you unit test In-App Purchase and Subscriptions
    - New StoreKit transaction manager shows details during debugging
    - Faster code completion with simplified presentation
  - **SwiftUI**
    - All SwiftUI apps will continue to compile without additional changes (Apple added no breaking changes - just extensions)
    - **Lazy** statement makes large collections of views way less memory hungry and makes scolling snappy again
    - Now contains app-structure APIs for all Apple platforms, e.g. `@main`, `@SceneBuilder`, `Settings`, ...

## Explore ARKit 4

https://developer.apple.com/wwdc20/10611

_Quinton Petty, Praveen Gowda_

* **Location Anchors**
	* Geo-referenced AR Content
	* Uses "visual localisation" from Maps
		* No processing in the cloud
		* No images sent back to Apple
	* Pinned to a geo-location
	* 3 main parts
		* [`ARGeoTrackingConfiguration`](https://developer.apple.com/documentation/arkit/argeotrackingconfiguration)
		* [`ARGeoAnchor`](https://developer.apple.com/documentation/arkit/argeoanchor)
		* [`ARGeotrackingStatus`](https://developer.apple.com/documentation/arkit/argeotrackingstatus)
	* Device support A12 Bionic or later + GPS support
	* Requires availablity checks for both device and location
	* [`ARGeotrackingStatus`](https://developer.apple.com/documentation/arkit/argeotrackingstatus)
		* [`State`](https://developer.apple.com/documentation/arkit/argeotrackingstatus/3580876-state)
		* [`StateReason`](https://developer.apple.com/documentation/arkit/argeotrackingstatus/statereason)
		* [`accuracy`](https://developer.apple.com/documentation/arkit/argeotrackingstatus/3580875-accuracy): low, medium, high
	* Methods for converting between local and latitude / longitude positions via `getGeoLocation(forPoint:)`
	* Recommended to point towards buildings / static objects
	* May struggle in wide open spaces (e.g a field)
	* [Locations currently available](https://developer.apple.com/documentation/arkit/argeotrackingconfiguration/3571351-checkavailability): San Francisco Bay Area, Los Angeles, New York, Chicago and Miami
	* Sample: [Tracking Geographic Locations in AR](https://developer.apple.com/documentation/arkit/tracking_geographic_locations_in_ar)
* **Scene Geometry**
	* Topological map of environment
	* Semantic classification
	* Allowing for:
		* Occlusion
		* Physics
		* Virtual lighting
	* Based upon the Depth API
* **Depth API**
	* Provides a dense depth image
	* Use [`sceneDepth`](https://developer.apple.com/documentation/arkit/arframe/3566299-scenedepth) under frame semantics
	* Provides dense depth image
	* Runs at 60Hz, on every ARFrame
	* [`depthMap`](https://developer.apple.com/documentation/arkit/ardepthdata/3566296-depthmap) and [`confidenceMap`](https://developer.apple.com/documentation/arkit/ardepthdata/3566295-confidencemap) provided
	* Depth map provided as `CVPixelBuffer`
	* [`ARConfidenceLevel`](https://developer.apple.com/documentation/arkit/arconfidencelevel): high, medium or low
	* Available on LiDAR devices
* **Object Placement**
	* Improvements in Raycasting
	* Quicker placement with LiDAR sensor
	* Allows for placing on a white wall
	* Raycasting is recommend over hit-testing
	* 2 types of query:
		* Raycast
		* Tracked Raycasts
* **Face Tracking**
	* Support added for non-TrueDepth iPhones
	* Requires A12 processor or later
	* iPhone SE (2020)
