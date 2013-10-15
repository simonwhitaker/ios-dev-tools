# iOS Dev Tools

The software I use when I'm writing software.

## Editing code

* [Monokai Xcode 4 Theme](https://github.com/riveralabs/monokai-xcode4-theme) is the syntax highlighting theme I like
* [SourceTree](http://www.sourcetreeapp.com) is my Git GUI client of choice
* [Kaleidoscope](http://www.kaleidoscopeapp.com) is great for resolving merge conflicts and general diffing
* I like [Sublime Text 2](http://www.sublimetext.com/2) as a general text editor, despite its many quirks
* [CodeRunner](http://krillapps.com/coderunner/) is great for quickly testing out snippets of code
* [xctool](https://github.com/facebook/xctool) is a replacement for Apple's `xcodebuild` tool but with saner output

## Xcode plugins

I don't use a lot of Xcode plugins, but these ones are useful enough to have been offered sanctuary in my ~/Library

* [KSImageNamed](https://github.com/ksuther/KSImageNamed-Xcode) adds auto-complete to `-[UIImage imageNamed:]`
* [ColorSense for Xcode](https://github.com/omz/ColorSense-for-Xcode) adds an inline colour picker to various `UIColor` methods

## Tweaking and debugging

* [xScope](http://iconfactory.com/software/xscope) is great for achieving pixel-perfect results in your UIs
* [Spark Inspector](http://www.sparkinspector.com) lets you visualise UIView hierarchies at runtime
* I use [PhoneView](http://www.ecamm.com/mac/phoneview/) if I need to poke around the file system of an iOS device
* [Quick Radar](http://www.quickradar.com) makes filing bug reports with Apple a cinch
* [SimPholders](http://simpholders.com) sits in your menu bar and gives quick access to the app folders for the iOS Simulator

## Debugging web services

* I use [Charles Proxy](http://www.charlesproxy.com) to see what's happening on the network when an app is running. (See [Using Charles from an iPhone](http://www.charlesproxy.com/documentation/faqs/using-charles-from-an-iphone/) for instructions on how to see the traffic going to and from a local device.)
* [Postman for Chrome](http://www.getpostman.com) is an HTTP client for testing RESTful web services. I use this a *lot*.
* [jq](http://stedolan.github.io/jq/) is a command-line JSON parser and mangler. It takes some learning, but it's a great tool for picking the stuff you care about out of a big load of JSON. (Tip: pipe a JSON stream through `jq '.'` to format it.)

## Core Data

* [mogenerator](https://github.com/rentzsch/mogenerator) keeps auto-generated Core Data entity classes and your higher-level logic separate. A must-have if you're working with Core Data.
* [Core Data Editor](http://christian-kienle.de/CoreDataEditor) is a GUI tool for browsing Core Data persistent stores. (Tip: double-click an item to see and navigate its relationships.)
* [Base](http://menial.co.uk/base/) is a general-purpose SQLite GUI – sometimes it's quicker to just open a Core Data SQLite DB in Base than it is to use Core Data Editor, since CDE generally needs reconfiguring if your data model or the location of the persistent store changes.

## Screencasting

* [Reflector](http://reflectorapp.com) is a stroke of pure genius: it lets you record screen activity on an iOS device by simply making itself available as an AirPlay target. Set your iOS device to mirror to it and you're good to go. File under *damn, I wish I'd thought of that*.
* I love [ScreenFlow](http://www.telestream.net/screenflow/) for screencasts from my Mac. I've tried a few screencasting apps over the years and this one is the best of the bunch.

## Deployment and beyond

* After years as a TestFlight user I switched to [HockeyApp](http://hockeyapp.net) and never looked back. [HockeyMac](https://rink.hockeyapp.net/apps/67503a7926431872c4b6c1549f5bd6b1) is the native companion app that makes uploading to HockeyApp as part of the Xcode archiving process a doddle.
* [Tokens](http://usetokens.com) helps you manage promo codes with zero hassle

## Miscellaneous

Not really development tools, but useful adjuncts to my day-to-day workflow.

* [Droplr](https://droplr.com) has a [great native Mac app](https://itunes.apple.com/gb/app/droplr/id498672703?mt=12) and an equally [great native iOS app](https://itunes.apple.com/gb/app/droplr/id500264329?mt=8). I use it every day for sharing links, code snippets and most of all images with my colleagues.
* [Pupil](http://www.pupil.io) lets me switch the display resolution on my MacBook Pro Retina easily

