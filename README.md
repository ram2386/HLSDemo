# HLS demo
A demo for playing M3U8 by AVPlayer in Swift which reading url from M3U8 file for streaming.

## Requirements
 - iOS 14.0+
 - Xcode 13.0+
 - Swift 5.0+

## Usage
- Setting the sample M3U8 url(http://qthttp.apple.com.edgesuite.net/1010qwoeiuryfg/sl.m3u8) to AVPlayer.
- Use play() / pause() to playing / pause the player.  
- AVPlayer does not have "stop", just to pause it and set it to nil.  

## Note
If you access the http url without **s** then please make sure you have to set "App Transport Security Settings" and "Allow Arbitrary Loads" to "YES".  
